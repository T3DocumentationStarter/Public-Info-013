======================================================
Breaking: Replace beLayout with backend grid templates
======================================================

Description
===========

Whenever a page or an FCE holds content elements (FCE used as grid), one had the possibility to define the arrangement
of the columns by defining a so called beLayout. In the context of TemplaVoilà, a beLayout is a snippet of HTML, it is
not a backend layout, provided by the core.

**Example**::
   <beLayout><![CDATA[
      <table width="100%">
         <tr>
            <td valign="top" width="100%" colspan="2">###field_header###</td>
         </tr>
         <tr>
            <td valign="top" width="70%">###field_content###</td>
            <td valign="top" width="30%">###field_rightsidebar###</td>
         </tr>
      </table>
   ]]></beLayout>
