[Chattanooga Open Data Policy](#bookmark=id.60ghvwhuu6ok)

[Chattanooga Open Data Spec](#bookmark=id.s5unwy7yhmjx)

**Chattanooga Open Data Policy**

[http://citycamp.govfresh.com/how-to-get-your-city-to-pass-an-open-government-policy/](http://citycamp.govfresh.com/how-to-get-your-city-to-pass-an-open-government-policy/)

**RESOLUTION NO. (2013) ____**

**A RESOLUTION INDICATING THE INTENT OF THE CITY TO CREATE AN OPEN GOVERNMENT BY ENCOURAGING THE USE OF OPEN SOURCE SYSTEMS AND ENSURING OPEN ACCESS TO PUBLIC DATA**

**WHEREAS, **the City of Chattanooga is committed to using technology to foster open, transparent, and accessible government; and

**WHEREAS, **by sharing data freely, the City of Chattanooga seeks to develop opportunities for economic development, commerce, increased investment and civic engagement; and

**WHEREAS,** the adoption of open standards improves transparency, access to public information, and improved coordination and efficiencies among organizations across the public, non-profit and private sectors; and

**WHEREAS,** open source standards harness the power of distributed peer review and transparency to create high-quality, secure and easily integrated software at an accelerated pace and lower cost; and

**WHEREAS, **the City of Chattanooga seeks to encourage the ideal software community to develop software applications and tools to collect, organize and share public data in new and innovative ways that benefit both citizens and government;

**NOW, THEREFORE, BE IT RESOLVED BY THE CITY COUNCIL OF THE CITY OF CHATTANOOGA:**

**Section 1.** That the City of Chattanooga Information Services Division will establish an open systems procurement policy that will include specifications in future Requests for Proposals (RFP) to encourage technology solutions with an open source licensing model which store and expose public data using industry-standard and open protocols.

**Section 2. **The City of Chattanooga will establish an open data website at www.chattanooga.gov/opendata that will serve as an open data portal of the data available from the City of Chattanooga in open formats as spelled out in the open data standard. 

**Section 3. **The City of Chattanooga Information Services Division will adopt open data standards for the publishing of data to the open data website.

**Section 4. **The City of Chattanooga Information Services Division, in coordination with city departments,  will publish a list of all city data sets and specify whether or not it has been opened and if not, why. 

**Section 5. **Each city department will identify and publish three priority datasets maintained within the department to the open data website by (six months from date of resolution). 

**City of Chattanooga– Open Data Standards**

**_Adapted from City of Raleigh Open Data Standards_**

**Underlying Principles**

The City of Chattanooga’s Open Data policy should operate under the following principles, taken from the[ Open Data Handbook](http://opendatahandbook.org/en/what-is-open-data/index.html).

* **_Availability and Access:_*** the data must be available as a whole and at no more than a reasonable reproduction cost, preferably by downloading over the internet. The data must also be available in a convenient and modifiable form.*

* **_Reuse and Redistribution:_*** the data must be provided under terms that permit reuse and redistribution including the intermixing with other datasets.*

* **_Universal Participation:_*** everyone must be able to use, reuse and redistribute - there should be no discrimination against fields of endeavour or against persons or groups. For example, ‘non-commercial’ restrictions that would prevent ‘commercial’ use, or restrictions of use for certain purposes (e.g. only in education), are not allowed.*

# Guidelines

## Content Guidelines

<table>
  <tr>
    <td>Guideline</td>
    <td>Example</td>
  </tr>
  <tr>
    <td>Open data sets should not include data that is prohibited by law or city policy to be open

</td>
    <td>Citizen financial information, public safety information that is not public, data that could compromise citizen privacy, or the security of city services</td>
  </tr>
  <tr>
    <td>Open data sets should be prioritized by citizens and city departments based on usefulness and ease of publishing</td>
    <td>Citizens can vote on data sets using an online forum for open data at openchattanooga.com.  City departments will analyze data sets that rise to the top to determine which are feasible and can be accomplished quickly.</td>
  </tr>
  <tr>
    <td>When evaluating whether data can or should be published as open data, the default position should be to make the data available unless there is a reason not to (sensitive data, data protected by law, etc).</td>
    <td>If data falls under a public records retention schedule, it should be allowed to be published.  Essentially, if there is not a reason (by law or to maintain the security of citizens or government services), the decision should be made to make the data available.</td>
  </tr>
  <tr>
    <td>Open data sets should contain as many data fields as is feasible and should include both unique identifiers useful for automated processing and analysis and human-readable descriptors</td>
    <td>If a permit type has both a numerical code (E38) and a descriptor (Electrical Permit), both fields should be included to expand the potential use of the data set. IDs automatically generated by databases should also be included (where applicable).</td>
  </tr>
  <tr>
    <td>Open data sets should be read-only, so the source data does not change</td>
    <td>City departments should not have to worry that their source data, which is used in the delivery of citizen services, will be changed without their knowledge or permission
</td>
  </tr>
  <tr>
    <td>Fields should use meaningful names, and not cryptic descriptors, with a common convention.</td>
    <td>Use meaningful names that the average person will understand, like "Address", or “PermitNumber”, and use a CamelCase format that is friendly for programming and data analysis (no spaces, special characters, etc)</td>
  </tr>
</table>


## Format Guidelines

<table>
  <tr>
    <td>Guideline</td>
    <td>Example</td>
  </tr>
  <tr>
    <td>Data should be in machine-readable format</td>
    <td>Instead of posting a PDF with a tabular listing of data, post a comma-separated or tab-separated text document instead.
</td>
  </tr>
  <tr>
    <td>Data should be in formats that encourage the direct use of the data through application programming interfaces (API’s)</td>
    <td>Data can be posted on a web server with a permanent Uniform Resource Locator (URL) in a standardized data exchange format, such as JSON or XML.</td>
  </tr>
  <tr>
    <td>Data should be provided in its original form and (to the greatest extent feasible) be in open or commonly used formats that are platform independent.</td>
    <td>A user of the data should not have to pay for a proprietary software package or programming library to read or consume the data. Therefore, a spreadsheet should be posted in OpenDocument format (.ods) or CSV along with the proprietary Microsoft Excel format (.xlsx).
</td>
  </tr>
  <tr>
    <td>Data should be presented in "raw" form and should additionally include a version without presentational formatting.</td>
    <td>Data should be given in its entire raw form. If it contains presentational markup (e.g. HTML such as <table>, <p>, <br>), then an alternate version with the markup removed should be included as well.</td>
  </tr>
  <tr>
    <td>Data that includes time should include the time zone.</td>
    <td>Wherever possible, the time zone should be included with the data. It is preferred to use UTC for all time based entries. This would allow a developer to display the correct time based on the user’s location.</td>
  </tr>
  <tr>
    <td>Data should be published in a variety of formats so that the greatest number of uses (technical and nontechnical) can benefit from it. </td>
    <td>The more formats available for the data the better. Multiple geographic formats should also be available including KML, shapefile and geoJSON.</td>
  </tr>
</table>


**Publishing Process Guidelines**

<table>
  <tr>
    <td>Guideline</td>
    <td>Example</td>
  </tr>
  <tr>
    <td>Each data set should have an identified business system owner who is responsible for the accuracy of the source data</td>
    <td>For instance, the business system owner for the permitting and inspections system should be identified as the owner of the permits open data set.</td>
  </tr>
  <tr>
    <td>Each data set should have a field map that identifies the source system and field and how that maps to the open data catalog</td>
    <td>Being able to identify where exactly a specific field in the open data set came from in the source system is important for troubleshooting purposes and to guarantee the authority of the data set.</td>
  </tr>
  <tr>
    <td>The business system owner and application developer will work together to identify the appropriate publication method (automatic vs manual, schedule, technical method, etc)</td>
    <td>A data set that will be used for historical analysis may be best published using a manual process and updating manually at some interval (3 to 6 months).  A data set that could be used for more real-time services should be updated more frequently and thus should be programmed to update automatically.
</td>
  </tr>
  <tr>
    <td>Each data set should have documentation of the process used to convert the original format to the open format.</td>
    <td>When converting data from a proprietary format to an open format, documentation of the software and version numbers should be included. This allows the data to be reconverted in the future when software is updated.
</td>
  </tr>
  <tr>
    <td>Before publishing the data set, the business system owner should review the field map and the data that will be published to ensure that no sensitive data is being included in the open data set.</td>
    <td>An analysis of the data, public records law, and other pertinent laws related to identity theft protection or sensitive data. Final gatekeeper for review?</td>
  </tr>
  <tr>
    <td>If a data set is requested that contains sensitive information, staff should analyze whether the data set can be aggregated, generalized, or de-identified in some way to allow for the greatest amount of data to be published.</td>
    <td>If a data set contains a citizen identifier that would make the data sensitive (such as an address, or account number), staff should consider removing just those fields that make the data identifiable.  Or, data can be aggregated by street name, zip code or neighborhood to make it less sensitive.</td>
  </tr>
</table>


## Publishing Guidelines

<table>
  <tr>
    <td>Guideline</td>
    <td>Example</td>
  </tr>
  <tr>
    <td>Data should be updated frequently to ensure the greatest usefulness of the data</td>
    <td>Out of date permit data or assessment liens could reduce the value of the open data set by requiring users of the data to make a phone call to ensure they have the most up to date data.</td>
  </tr>
  <tr>
    <td>Data should be published in a way that easily identifies new and changed records</td>
    <td>Data should be time stamped to allow computer programs to determine which records were added and/or changed. Two timestamps should be included, one for when the record was created and one for when it was last changed. For instance, this would allow a mobile app to identify all permits issued in the last 30 days based on your location by filtering records by date.  </td>
  </tr>
  <tr>
    <td>Data should be published by automated means whenever possible in order to lessen the burden on city staff and to increase the usefulness of the data set</td>
    <td>Instead of relying on a staff member to update a data set daily or weekly, an interface program should be written to send the data to the open data catalog automatically based on a set schedule</td>
  </tr>
  <tr>
    <td>Data should be published in a way that allows both technical and non-technical users to gain value from the data set</td>
    <td>Wherever possible, data should be posted in multiple data formats, some specialized for writing applications (JSON or XML) and some specialized for human analysis (spreadsheets or an online visualization or mapping interface)</td>
  </tr>
</table>


Open Data Checklist 

1. Do the data fields have meaningful human readable names? 

2. Are the data fields in CamelCase (without special characters or spaces)? 

3. Is the data in a machine readable format (not pdf)? 

4. Is the data in an open format (csv, json, xml, odt, ect.) that does not require proprietary software?

5. Is the data in its raw form without formating? 

 

**Sources of Inspiration:**

* [http://wiki.civiccommons.org/Open_Data_Guidelines](http://wiki.civiccommons.org/Open_Data_Guidelines)

* [http://wiki.civiccommons.org/Open_Data_Policy](http://wiki.civiccommons.org/Open_Data_Policy)

* CIty of Raleigh - Open Data....

* City of Austin – Open Data Resolution ([http://www.ci.austin.tx.us/edims/document.cfm?id=161941](http://www.ci.austin.tx.us/edims/document.cfm?id=161941))

* The Open Data Handbook ([http://opendatahandbook.org/](http://opendatahandbook.org/))

* Sunlight Foundation – 10 principles for opening up government information ([http://sunlightfoundation.com/policy/documents/ten-open-data-principles/](http://sunlightfoundation.com/policy/documents/ten-open-data-principles/))

* Sunlight Foundation - Open Data Policy Guidelines

([http://sunlightfoundation.com/opendataguidelines/](http://sunlightfoundation.com/opendataguidelines/))

* City of Vancouver - Open Data Resolution -[ http://vancouver.ca/ctyclerk/cclerk/20090519/documents/motionb2.pdf](http://vancouver.ca/ctyclerk/cclerk/20090519/documents/motionb2.pdf)

* List of open data policies and guidelines -[ http://wiki.civiccommons.org/](http://wiki.civiccommons.org/)

* Cook County, Illinois- Open Government Plan[ http://blog.cookcountygov.com/opencc/wp-content/uploads/2011/09/Open_Cook_County_9.21.11.pdf](http://blog.cookcountygov.com/opencc/wp-content/uploads/2011/09/Open_Cook_County_9.21.11.pdf)

* NYC Open Data Standards Wiki:[ http://nycopendata.pediacities.com/wiki/index.php/NYC_Open_Data](http://nycopendata.pediacities.com/wiki/index.php/NYC_Open_Data)

* Economic argument for opening data

[radar.oreilly.com/tag/data-economy](http://radar.oreilly.com/tag/data-economy)

* Hawaii open data law

[http://www.capitol.hawaii.gov/measure_indiv.aspx?billtype=HB&billnumber=632](http://www.capitol.hawaii.gov/measure_indiv.aspx?billtype=HB&billnumber=632)

* Economic costs of not opening data

[http://blog.okfn.org/2011/10/17/the-cost-of-closed-data-the-economics-of-open-data/](http://blog.okfn.org/2011/10/17/the-cost-of-closed-data-the-economics-of-open-data/)

* Openwashing

[http://gov20.govfresh.com/beware-openwashing-question-secrecy-acknowledge-ideology/](http://gov20.govfresh.com/beware-openwashing-question-secrecy-acknowledge-ideology/)

* Missing Open Data Policy

[http://sunlightfoundation.com/blog/2012/03/22/the-missing-open-data-policy/](http://sunlightfoundation.com/blog/2012/03/22/the-missing-open-data-policy/)

* White House Open Data Policy Page

([http://project-open-data.github.io/?utm_source=brigade&utm_medium=page&utm_name=project-open-data](http://project-open-data.github.io/?utm_source=brigade&utm_medium=page&utm_name=project-open-data))

* Open Data Stackexchange

([http://opendata.stackexchange.com/](http://opendata.stackexchange.com/))


