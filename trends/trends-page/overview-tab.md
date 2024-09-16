# Overview tab

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>Market View Trends > Overview tab</p></figcaption></figure>

Look below the query paragraph in the blue header, and you'll see the [**Overview**](https://marketview.nais.org/trends) tab highlighted.

The [**Overview**](https://marketview.nais.org/trends) tab has three topics: [**Population Data**](overview-tab.md#the-population-data-subtab), [**Income Data**](overview-tab.md#the-income-data-subtab), and [**Diversity Data**](overview-tab.md#the-population-data-subtab-1).

## Population data

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

### The map

If you look to the right side of the page, you'll see a multicolored map. This map is called a **choropleth** (core-o-pleth).&#x20;

{% hint style="info" %}
A choropleth map is a type of statistical thematic map that uses intensity of color to correspond with an aggregate summary of a geographic characteristic within spatial enumeration units.
{% endhint %}

In our case, the choropleth represents total school-age population. Each shape outlined in gray is a ZIP code. The darkest blue shapes are ZIPs with the most children, and the light green ZIPs have the fewest children.

You'll see header text above the map. That's the title of the map, and also displays the data reflected in the map and the charts below. For example, "Total School-Age Population by ZIP Code within a 30-Minute drive of Washington, DC 20036-3425".&#x20;

You'll also see a "Download" button with icon. Clicking this button will download the map exactly as shown. <mark style="color:blue;">Before downloading, make sure to adjust your settings and parameters so that the map will show the data you need.</mark> Alternatively, you can screenshot the map if you like that better.

On the map, there is shape with a double blue line. This is called an [isochrone](../../info/glossary.md#isochrone) (ice-oh-crone).

{% hint style="info" %}
An [**isochrone map**](../../info/glossary.md#isochrone) is a map that depicts the a time parameter. Market View's isochrones portray an area accessible from a point within a certain time threshold.
{% endhint %}

[By our estimates](../../info/glossary.md#travel-time), anyone living within the area bounded by the double blue lines can commute to your school within the travel time you specified. You'll see these isochrones throughout the various pages of Market View.

At the top of the map, there is a dropdown selector. The default selection is "Total School-Age Population". Market View defines School-Age Population as 0-18. Click that menu, and you'll see other options. Selecting a different option will cause the map colors to change, reflecting the new values you've chosen.

If you hover your mouse over a ZIP on the map, you'll see a small white box appear in the upper right corner of the map. In the screenshot below, the user is hovering over Riverdale and so the box in the upper right shows the value Riverdale has for the selected value. In this case, "Enrolled PK-12 Private Schools".

![](<../../.gitbook/assets/image (13).png>)

In the box in the upper right, "20737" is the ZIP Code, "Riverdale" is the locality name, and "619" is the number of children in that ZIP enrolled in PK-12 Private Schools.&#x20;

Lastly, there is a gradated color scale below the map on the right. This scale shows the colors that reflect the minimum and maximum values, and their representative colors. &#x20;

### The data

Let's scroll down past the map.&#x20;

You'll see a table titled **Population Data**. This tabular layout is probably familiar to you.  Feel free to paste it into your spreadsheet editor of choice. From there you can make any custom charts or graphs you need, beyond the graphics available in Market View.

{% hint style="info" %}
All tabular data in Market View is copy and pastable into a spreadsheet.
{% endhint %}

[Read more about how and where we get our data.](../../market-views-data/)

### Next steps

At the bottom of the page, you'll find suggestions for next steps. These suggestions are intended to help you make the most of Market View, on your own or as discussion questions with your team.&#x20;



## Income data

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption><p>Overview > Income Data</p></figcaption></figure>

The [Income Data subtab](https://marketview.nais.org/trends/summary/income) empowers you to analyze median income in your area.

You'll notice the title for the map is "Family Median Income by ZIP Code within a XX-Minute drive of YY Location".

Let's break this down!

[**Family**](../../info/glossary.md#family) is a census designated descriptor. It is distinct from [**household**](../../info/glossary.md#household). Two unmarried adults are a household. Two married adults are a family. A single adult with a biological child is a family. The census considers people living together with a blood or marriage bond a family. Otherwise, it's a household. Two unmarried adults are a household until they have a child, and then they are considered a family.

You'll notice we use both designations in different places in Market View. Family income cuts off at $500,000, after that it is grouped into "$500k and over". Household income has granularity up to $750,000, after that it is grouped into "$750k and over".&#x20;

Unless otherwise specified, "Family" in Market View also means "Families with children". Children are people aged 0-18.&#x20;

The [**median income**](../../info/glossary.md#median-income) is the [income](https://en.wikipedia.org/wiki/Income) amount that divides a population into two equal groups, half having an income above that amount, and half having an income below that amount. It may differ from the [mean](https://en.wikipedia.org/wiki/Mean) (or [average](https://en.wikipedia.org/wiki/Average)) income.





## Diversity data

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Overview > Diversity Data</p></figcaption></figure>

The [Diversity Data subtab](https://marketview.nais.org/trends/summary/diversity) offers an overview of the racial and ethnic breakdown  within the selected rive-time parameter, set above.&#x20;

Remember, if you are ever unsure about the information being displayed, the titles are a great place to start. Here, you'll see that the title of the map is "Total Population by ZIP Code within a XX minute drive of YY location."&#x20;

This tab makes use of all of the functionality previously discussed in this guide- change the variable displayed in the choropleth map to view densities of a specific group, download the map, and view tabular data with five-year projections below.&#x20;

Wait! What is the difference between race and ethnicity?&#x20;

The Census considers race and ethnicity to be distinct concepts.&#x20;

_Race_ refers to the way a person self identifies with social group(s). The Census offers White, Black or African American, Asian, American Indian and Alaska Native Hawaiian and Other Pacific Islander, or some other race groupings. Participants can also report multiple races.&#x20;

_Ethnicity_ focuses on whether a person is of Hispanic origin or not.&#x20;
