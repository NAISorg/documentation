---
description: >-
  The power of Market View comes from making it customized to your school and
  community. Upload data to see it on the map, and analyze your enrollment
  pipeline.
---

# Upload data from spreadsheets

There are **two** types of data you can upload to Market View,[ student enrollment data](upload-data-from-spreadsheets.md#upload-student-enrollment-data) and [miscellaneous data](upload-data-from-spreadsheets.md#upload-miscellaneous-data). Because Market View is geographically driven, all data uploaded should have an address (a ZIP code at the very least).&#x20;

## Upload student enrollment data

You'll need one spreadsheet per year, containing all your applications _or_ enrollments for that year. Please use this template and fill it in with your data.

{% file src="../../.gitbook/assets/template-admission-data-market-view.csv" %}
Admission Data Template
{% endfile %}

For student data (applications and enrollments), the template contains five columns. We ask for Student ID so that one day we can show you attrition data, since it allows us to see when students move on to the next grade.&#x20;

{% hint style="info" %}
Please include all five columns and their titles in your spreadsheet, even if they are empty. The only column that requires a value is "Address", and that can be as minimal as a ZIP code. Note that you need to provide a full address to see students plotted on the map.&#x20;
{% endhint %}

<table><thead><tr><th width="142">First name</th><th width="136">Last name</th><th width="239">Address</th><th width="122">ID</th><th width="110">Grade</th></tr></thead><tbody><tr><td>Jane</td><td>Doe</td><td>2134 KALORAMA RD NW, WASHINGTON DC 20008</td><td>1ac</td><td>1</td></tr></tbody></table>

Next, navigate to [Your Data](https://marketview.nais.org/your-data). Drag and drop each file to the appropriate school year bucket.



***

## Upload miscellaneous data

You can upload any type of addresses into the Miscellaneous category. Schools upload bus stops, faculty addresses, competitor schools, coffee shop locations, anything that would be helpful to see plotted on the Market View map.

Miscellaneous data only needs a valid address, no title or name required.

{% file src="../../.gitbook/assets/template-miscellaneous-data-market-view.csv" %}
Miscellaneous data template
{% endfile %}

For miscellaneous data, the template contains four columns for each address. You can just upload a single column with the entire address as well, if it's easier. Market View concatenates the whole address before geocoding, so it doesn't matter how many columns you use as long as it's only one address per row.

| Address         | City      | State | ZIP   |
| --------------- | --------- | ----- | ----- |
| 456 Cherry Lane |  New York |  NY   | 12345 |

Next, navigate to [Miscellaneous Data](https://marketview.nais.org/your-data/miscellaneous). Drag and drop each file to the gray bucket. Note that the file name will be used to label this data set in Your Data, as well as in Map View.

Addresses on miscellaneous data uploads which appear more than once won't show up. If you have an address listed more than once per file, it won't show up on the map or the address counts.&#x20;

Any data that you uploaded prior to August 2022 was migrated to the Miscellaneous Data category. If that data would be better in the applications or enrollments categories, feel free to delete and re-upload. Please make sure you have a local copy of the data before you delete it from Market View, deletion is final. If you no longer have access to that data, and need to download it from Market View, [please reach out](https://my.nais.org/s/submit-a-ticket?category=DASL%2FDASL%20Insights) and we wil try to help you get access.

## International addresses

Whenever you upload or import address data to Market View, we attempt to geocode it. Geocoding is the process of converting an address into a latitude/longitude pair of coordinates.&#x20;

Often, international addresses will not geocode correctly. [Here is a map with the countries with the most accurate and least accurate geocoding. ](https://developers.arcgis.com/rest/geocode/api-reference/geocode-coverage.htm)

If your international address geocodes succesfully, you will see it on the map if you select that dataset's map layer. If the address doesn't geocode sucessfully, you will not see it plotted on the map.

After you upload your data, Market View will notify you if it had issues with any of the addresses. Feel free to delete the dataset, fix it, and try again. Often, putting the address into Google Maps and using the address the way Google formats it can be helpful.&#x20;



## Tutorial Video

{% embed url="https://vimeo.com/334799562" %}
How to upload addresses
{% endembed %}
