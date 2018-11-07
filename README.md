## Content API for Commerce.gov
Content on Commerce.gov is exposed in three REST APIs available at 
* [https://api.commerce.gov/api/blogs](https://api.commerce.gov/api/blogs?api_key=DEMO_KEY), 
* [https://api.commerce.gov/api/news](https://api.commerce.gov/api/news?api_key=DEMO_KEY), and 
* [https://api.commerce.gov/api/image](https://api.commerce.gov/api/image?api_key=DEMO_KEY). 

Full documentation is located and maintained at https://www.commerce.gov/page/api-documentation-commercegov

## Changelog:
* 11/9/2018 - News v2.0, Blogs v2.0, Image v2.0: Complete rewrite of the API to reflect the redesign of the Commerce.gov D8 website. API endpoints - news, blogs and image and their response fields preserved for backward compatibility. Advanced features such as returning specific fields, returning specific content, applying a query filter, applying a query sort, API versioning, and change request formatter are not available for this version. Fields with null values are returned as string with null value. Example "null".
* 9/23/2016 - Image v1.0: Initial release of API resource endpoint for Images/Photos. Added image specific fields to field reference and updated resource column.
* 12/5/2015 - News v1.0: Initial release of API resource endpoint for Newsroom content. Added newsroom specific fields to field reference and new column to show which fields are available for which content types.
* 10/07/2015 - Documentation updated for additional query filter operators.
* 10/05/2015 - Documentation updated to reflect query filter operator limitations and working example for simple filter on label field.
* 09/29/2015 - Blog v1.0: Initial release includes API resource endpoint for Blog content only.

## Periodic updates

The Commerce.gov API is under active, but not public, development. As such, API code is not currently made available publically. This Github repository will be used to collect and respond to feedback regarding the API and engage with developers interested in using the API.
