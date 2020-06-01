-----------------------
-***** ADMIN API *****-
-----------------------

1) QueryRoot

API version (2020-04 Latest)
The schema's entry-point for queries. This acts as the public, top-level API from which all queries must start.

x-----------------x---------------x-------------x---------------x---------------x

2) Queryable objects

Queryable objects represent the resources that you can access
AllDiscountItems
ApiVersion
Attribute
AutomaticDiscountApplication
BasicEvent
BulkOperation
CalculatedDraftOrder 
CalculatedLineItem
CalculatedOrder
Channel
Collection 
CollectionPublication
CollectionRuleConditions
CommentEvent 
Customer
CustomerVisit
DeletionEvent
DeliveryCarrierService 
DeliveryCarrierServiceAndLocations
DeliveryCondition
DeliveryCountry 
DeliveryLocationGroup
DeliveryMethodDefinition
DeliveryParticipant 
DeliveryProfile 
DeliveryProvince
DeliveryRateDefinition
DeliverySetting 
DeliveryZone
DiscountAllocation
DiscountAmount
DiscountAutomaticBasic
DiscountCodeApplication
DiscountCodeBasic
DiscountCodeFreeShipping
DiscountCollections
DiscountCountries
DiscountCountryAll
DiscountCustomerAll
DiscountCustomerBuys
DiscountCustomerGets
DiscountCustomers
DiscountCustomerSavedSearches
DiscountMinimumQuantity
DiscountMinimumSubtotal
DiscountOnQuantity 
DiscountPercentage
DiscountProducts
DiscountPurchaseAmount
Domain
DraftOrder
DraftOrderAppliedDiscount
DraftOrderLineItem
EditableProperty
ExternalVideo
Fulfillment 
FulfillmentEvent
FulfillmentLineItem
FulfillmentOrder 
FulfillmentOrderDestination
FulfillmentOrderLineItem
FulfillmentOrderMerchantRequest
FulfillmentService 
Image
InventoryItem 
InventoryLevel
LineItem
LineItemMutable
Locale
Location 
MailingAddress
ManualDiscountApplication
NavigationItem
OnlineStoreArticle
OnlineStoreBlog
OnlineStorePage
Order 
OrderDisputeSummary
OrderStagedChangeAddCustomItem
OrderStagedChangeAddVariant
OrderStagedChangeDecrementItem
OrderStagedChangeIncrementItem
OrderTransaction
PriceRule 
PriceRuleDiscountCode
PriceRuleEntitlementToPrerequisiteQuantityRatio
PriceRuleFixedAmountValue
PriceRuleMoneyRange
PriceRulePercentValue
PricingPercentageValue
PrivateMetafield
Product 
ProductOption
ProductPublication
ProductVariant 
Publication
PublishedTranslation
Refund
RefundDuty
RefundLineItem
ResourceFeedback
ResourcePublication
SavedSearch 
ScriptDiscountApplication
ScriptTag
ShippingLine
Shop 
ShopLocale
StagedMediaUploadTarget 
StagedUploadTarget 
StorefrontAccessToken
TaxLine
TenderTransaction
TenderTransactionCreditCardDetails
TranslatableResource 
UTMParameters
Video
VideoSource
WebhookSubscription
Weight

x-----------------x---------------x-------------x---------------x---------------x

3) Mutations

defines all the write operations that can change data. It is analogous to performing HTTP verbs such as POST, PATCH, and DELETE.
Input Objects 
bulkOperationCancel
bulkOperationRunQuery
collectionAddProducts
collectionCreate
collectionDelete
collectionRemoveProducts
collectionReorderProducts
collectionUpdate
customerAddTaxExemptions
customerCreate
customerDelete
customerGenerateAccountActivationUrl
customerRemoveTaxExemptions
customerReplaceTaxExemptions
customerUpdate
customerUpdateDefaultAddress
deliveryProfileCreate
deliveryProfileRemove
deliveryProfileUpdate
deliverySettingUpdate
deliveryShippingOriginAssign
discountAutomaticActivate
discountAutomaticBasicCreate
discountAutomaticBasicUpdate
discountAutomaticBulkDelete
discountAutomaticDeactivate
discountAutomaticDelete
discountCodeActivate
discountCodeBasicCreate
discountCodeBasicUpdate
discountCodeDeactivate
discountCodeDelete
discountCodeFreeShippingCreate
discountCodeFreeShippingUpdate
draftOrderCalculate
draftOrderComplete
draftOrderCreate
draftOrderDelete
draftOrderInvoicePreview
draftOrderInvoiceSend
draftOrderUpdate
flowTriggerReceive
fulfillmentCancel
fulfillmentCreateV2
fulfillmentOrderAcceptCancellationRequest
fulfillmentOrderAcceptFulfillmentRequest
fulfillmentOrderCancel
fulfillmentOrderClose
fulfillmentOrderMove
fulfillmentOrderRejectCancellationRequest
fulfillmentOrderRejectFulfillmentRequest
fulfillmentOrderSubmitCancellationRequest
fulfillmentOrderSubmitFulfillmentRequest
fulfillmentServiceCreate
fulfillmentServiceDelete
fulfillmentServiceUpdate
fulfillmentTrackingInfoUpdateV2
inventoryActivate
inventoryAdjustQuantity
inventoryBulkAdjustQuantityAtLocation
inventoryDeactivate
inventoryItemUpdate
kitSkillTriggerRequest
marketingActivityUpdate
marketingEngagementCreate
metafieldDelete
metafieldStorefrontVisibilityCreate
metafieldStorefrontVisibilityDelete
orderCapture
orderClose
orderEditAddCustomItem
orderEditAddVariant
orderEditBegin
orderEditCommit
orderEditSetQuantity
orderMarkAsPaid
orderOpen
orderUpdate
priceRuleActivate
priceRuleCreate
priceRuleDeactivate
priceRuleDelete
priceRuleDiscountCodeCreate
priceRuleDiscountCodeUpdate
priceRuleUpdate
privateMetafieldDelete
privateMetafieldUpsert
productAppendImages
productCreate
productCreateMedia
productDelete
productDeleteImages
productDeleteMedia
productDuplicate
productImageUpdate
productReorderImages
productReorderMedia
productUpdate
productUpdateMedia
productVariantCreate
productVariantDelete
productVariantUpdate
publishablePublish
publishablePublishToCurrentChannel
publishableUnpublish
publishableUnpublishToCurrentChannel
refundCreate
savedSearchCreate
savedSearchDelete
savedSearchUpdate
scriptTagCreate
scriptTagDelete
scriptTagUpdate
shippingPackageDelete
shippingPackageMakeDefault
shippingPackageUpdate
shopLocaleDisable
shopLocaleEnable
shopLocaleUpdate
stagedUploadsCreate
stagedUploadTargetGenerate
stagedUploadTargetsGenerate
storefrontAccessTokenCreate
storefrontAccessTokenDelete
tagsAdd
tagsRemove
translationsRegister
translationsRemove
webhookSubscriptionCreate
webhookSubscriptionDelete
webhookSubscriptionUpdate

x-----------------x---------------x-------------x---------------x---------------x

4) Custom scalars

queries and responses take the form of a hierarchical tree

x-----------------x---------------x-------------x---------------x---------------x

5) REST Admin API reference

The REST Admin API lets you build web/app and other integrations for the admin
Access 
Analytics 
Billing 
Customers 
Discounts 
Events 
Inventory
Online store 
Orders 
Plus 
Products 
Sales channel 
Shipping and fulfillment 
Payments 
Store properties 
TenderTransaction

x-----------------x---------------x-------------x---------------x---------------x

6) Admin API access scopes

 authorization process

x-----------------x---------------x-------------x---------------x---------------x

---------------------------
-***** Front end API *****-
---------------------------

1) Getting started

The Front end API can only be accessed using Admin API
Front end API provides unauthenticated access to customers, checkouts, product collections, and other store resources that you can use to build purchasing experiences

x-----------------x---------------x-------------x---------------x---------------x

2) Front end API reference

Using the front end API, you can:

Fetch data about a single product or a collection of products to display on any website or device.
Create unique checkout experiences with full control over the shopping cart.
Create new customers or modify existing ones, including address information.
Allow customers to select unique product options.

Front end API is Connected with the following attributes of ADMIN API
QueryRoot
Custom scalars
Mutations 
Queryable objects 

x-----------------x---------------x-------------x---------------x---------------x

3) Front end API access scopes

Unauthenticated access is intended for interacting with a store on behalf of a customer to perform actions such as viewing products or initiating a checkout.

x-----------------x---------------x-------------x---------------x---------------x

------------------------
---***** THEMES *****---
------------------------

1) Getting started with the Liquid markup language

Language to build webpages that combine static content, which is the same on multiple pages, and dynamic content, which changes from one page to the next
The static elements are written in HTML, and the dynamic elements are written in Liquid.
When the code in the file is compiled and sent to the browser, the Liquid is replaced by data from the Spring where the theme is installed.

Three main features of Liquid code:

Objects --> 

{{ product.title }}

Tags -->  

{% if product.available %}
  <h2>Price: $99.99</h2>
  {% else %}
  <h2 class="sold-out">Sorry, this product is sold out.</h2>
  {% endif %}

  tags are categorized into various types:

Control flow tags
Iteration tags
Theme tags
Variable tags

Filters -->

  {{ 'hello, world!' | capitalize }}

  They are categorized into 8 types:

Array filters
Color filters
HTML filters
Math filters
Money filters
String filters
URL filters
Additional filters

x-----------------x---------------x-------------x---------------x---------------x

2) language reference

Liquid language is written in Ruby.Liquid is the backbone of all themes, and is used to load dynamic content to the pages of online stores.

x-----------------x---------------x-------------x---------------x---------------x

3) Ajax API

Allows developers to build creative, interactive buying experiences into themes. By interacting with its JSON endpoints, you can update the shopping cart and display suggested products without requiring page refreshes in the browser.
Such as:
Cart
Product
Product recommendations
Predictive search

x-----------------x---------------x-------------x---------------x---------------x

4) Themes files

Themes are composed of files that control the look and feel of different pages of the online store. All files are coded in Liquid.
404.liquid
article.liquid
blog.liquid
cart.liquid
collection.liquid
customers/account.liquid
customers/activate_account.liquid
customers/addresses.liquid
customers/login.liquid
customers/order.liquid
customers/register.liquid
customers/reset_password.liquid
gift_card.liquid
index.liquid
list-collections.liquid
page.liquid
password.liquid
product.liquid
search.liquid
theme.liquid

x-----------------x---------------x-------------x---------------x---------------x

5) Sections architecture

For testing the sections architecture which includes:
Theme frames
Frame sections
Page sections
Content sections
Content schema
Master pages
Section rendering API

x-----------------x---------------x-------------x---------------x---------------x

6) Configuring theme settings

settings_schema.json file controls the organization and content of the menu

x-----------------x---------------x-------------x---------------x---------------x

--------------------------------
---***** WEB EXTENSIONS *****---
--------------------------------

1) Extension areas

You should familiarize yourself with the admin so you can choose the best way to integrate your app

x-----------------x---------------x-------------x---------------x---------------x

--------------------------
-***** OhMyCode POS *****-
--------------------------

1) Getting started

The first thing that you need to do is enable the POS Extension so that your WEB is available to be embedded in POS.

x-----------------x---------------x-------------x---------------x---------------x

2) POS cart extension reference

This reference describes the fields that sends to your web for each of the different endpoint calls. The reference also includes the response fields and possible values for the templates and actions that your web sends to server.

x-----------------x---------------x-------------x---------------x---------------x

--------------------------
--***** AngularJS *****---
--------------------------

Strcutural Framework for dynamic web apps
It contains everything developers require while building dynamic single page application.
AngularJS concepts:
Directives to extend HTML attributes.
Expressions to bind data to HTML.
Scope to control variables.
Two-way data binding.
Rendering of HTML.
Event-handling.
Composability.
Unit testing.
Controllers.
Services
Routing.

x-----------------x---------------x-------------x---------------x---------------x

--------------------------
--***** SpringBoot *****--
--------------------------

Spring Boot is a Framework from “The Spring Team” to ease the bootstrapping and development of new Spring Applications.
It provides defaults for code and annotation configuration to quick start new Spring projects within no time.
Advantages of Spring Boot:
It is very easy to develop Spring Based applications with Java or Groovy.
It reduces lots of development time and increases productivity.
It avoids writing lots of boilerplate Code, Annotations and XML Configuration.
It is very easy to integrate Spring Boot Application with its Spring Ecosystem like Spring JDBC, Spring ORM, Spring Data, Spring Security etc.
It follows “Opinionated Defaults Configuration” Approach to reduce Developer effort
It provides Embedded HTTP servers like Tomcat, Jetty etc. to develop and test our web applications very easily.
It provides CLI (Command Line Interface) tool to develop and test Spring Boot(Java or Groovy) Applications from command prompt very easily and quickly.
It provides lots of plugins to develop and test Spring Boot Applications very easily using Build Tools like Maven and Gradle
It provides lots of plugins to work with embedded and in-memory Databases very easily.

x-----------------x---------------x-------------x---------------x---------------x

---------------------------------------------------------------
--***** Integrating an Angular project with Spring Boot *****--
---------------------------------------------------------------

Step 1: setup your Spring Boot application
When you’re all setup and ready, open the project with your favorite IDE. Your directory structure should look something like this:
(SRC Is produced)

Step 2: Setup a restcontroller quickly and get a response back from the web server to make sure everything is working fine:
(Localhost Nav working properly)

Step 3: setup your Angular application
Start by creating a new directory called (environment) (spring src).
Run the command ng new (OhMyCodeAngular) to create a new angular project within our Spring Boot project

Step 4: To change the configuration in such a way that Angular can build it’s files and provides them for Spring Boot to use. To do that we edit the (angular.json) file and change the outputPath value to generate the build files in src  of the project.

Step 5: To inform Maven that the Angular project needs to be compiled first before the Spring Boot files we need to inset a plugin into the pom.xml file in Spring

Step 6: package your project
From the root of the project, type mvn package. Maven will now build the Angular project and place the files in the public directory

x-----------------x---------------x-------------x---------------x---------------x

--------------------------
----***** MySQL *****-----
--------------------------

MySQL is a freely available open source Relational Database Management System (RDBMS) that uses Structured Query Language (SQL). SQL is the most popular language for adding, accessing and managing content in a database. It is most noted for its quick processing, proven reliability, ease and flexibility of use

x-----------------x---------------x-------------x---------------x---------------x

---------------------------------------------------------------
--------***** Configuring Spring Boot for MySQL *****----------
---------------------------------------------------------------

Naturally, Spring Boot has support for MySQL 

Step 1: MySQL Configuration
You’ll need to have a database defined for your use. For this example, I want to create a database for my use. Using the command prompt, you can log into MySQL with this command:

>>>mysql -u root

Use the following command to create a database.

>>>CREATE DATABASE springbootdb;

You only need to use these commands if you want to use a new database.

Step 2: MySQL Dependencies
First we need to add the MySQL database drivers to our project. You will need to add the following dependency to your Maven POM file.

POM.xml
        <dependency>
            <groupId>mysql</groupId>
            <artifactId>mysql-connector-java</artifactId>
        </dependency>

Step 3: Spring Boot Properties
We need to override the H2 database properties being set by default in Spring Boot.w
When we configure MySQL for use. Spring Boot wont setup the H2 database anymore.

The following properties are need to configure MySQL with Spring Boot.Using JPA too to configure Hibernate for MySQL too.

>>>spring.datasource.url= jdbc:mysql://localhost:3306/springbootdb
>>>spring.datasource.username=root
>>>spring.datasource.password=
>>>spring.jpa.hibernate.ddl-auto=create-drop

Step 4: Running Spring Boot with MySQL
This is all that needs to be changed to use MySQL with Spring Boot. When you start the project now, MySQL will be used by the Spring Boot application for the database.

x-----------------x---------------x-------------x---------------x---------------x

--------------------------
----***** LIQUID *****----
--------------------------

Liquid is a language that allows us to display data in a template
Liquid has constructs such as output, logic, loops and deals with variables
Liquid files are a mixture of HTML and Liquid code, and have the .liquid file extension
Liquid files used in a theme are agnostic and have no concept of the store they are currently being used in
The two types of delimiters used in Liquid
How to output data from a store in a Liquid file
How to manipulate data with filters
How to loop over a Liquid collection to output multiple items
The use of logic in a Liquid file
The different types of operators used for comparison
How to control whitespace in Liquid

Liquid code can be categorized into objects, tags, and filters.

Objects tell Liquid where to show content on a page. Objects and variable names are denoted by double curly braces: {{ and }}.

Input


{{ page.title }}

Output

Introduction

Tags create the logic and control flow for templates. They are denoted by curly braces and percent signs: {% and %}.

The markup used in tags does not produce any visible text. This means that you can assign variables and create conditions and loops without showing any of the Liquid logic on the page.

Input


{% if user %}
  Hello {{ user.name }}!
{% endif %}

Output

Hello Adam!

Tags can be categorized into three types:

Control flow (if/else)
Iteration (loop)
Variable assignments (bool)

Filters change the output of a Liquid object. They are used within an output and are separated by a |.

Input


{{ "/my/fancy/url" | append: ".html" }}

Output

/my/fancy/url.html

Liquid includes many logical and comparison operators.

Basic operators
==	equals
!=	does not equal
>	greater than
<	less than
>=	greater than or equal to
<=	less than or equal to
or	logical or
and	logical and

contains
contains checks for the presence of a substring inside a string.


{% if product.title contains "Pack" %}
  This product's title contains the word Pack.
{% endif %}

Liquid objects can have one of five types:

String
Number
Boolean
Nil
Array

String
Declare a string by wrapping a variable’s value in single or double quotes:


{% assign my_string = "Hello World!" %}

Number
Numbers include floats and integers:


{% assign my_int = 25 %}
{% assign my_float = 39.756 %}

Boolean
Booleans are either true or false. No quotations are necessary when declaring a boolean:


{% assign foo = true %}
{% assign bar = false %}

Accessing specific items in arrays
You can use square bracket [ ] notation to access a specific item in an array. Array indexing starts at zero.

Input


<!-- if site.users = "Tobi", "Laura", "Tetsuro", "Adam" -->
{{ site.users[0] }}
{{ site.users[1] }}
{{ site.users[3] }}

Output

Tobi
Laura
Adam

Whitespace control
In Liquid, you can include a hyphen in your tag syntax {{-, -}}, {%-, and -%} to strip whitespace from the left or right side of a rendered tag.

Normally, even if it doesn’t print text, any line of Liquid in your template will still print a blank line in your rendered HTML:

Input


{% assign my_variable = "tomato" %}
{{ my_variable }}

Notice the blank line before “tomato” in the rendered template:

Output


tomato

Comment
Allows you to leave un-rendered code inside a Liquid template. Any text within the opening and closing comment blocks will not be printed, and any Liquid code within will not be executed.

Input


Anything you put between {% comment %} and {% endcomment %} tags
is turned into a comment.

Output

Anything you put between  tags
is turned into a comment.

for
Repeatedly executes a block of code. For a full list of attributes available within a for loop, see forloop (object).

Input


{% for product in collection.products %}
  {{ product.title }}
{% endfor %}

Output

hat shirt pants

break
Causes the loop to stop iterating when it encounters the break tag.

Input


{% for i in (1..5) %}
  {% if i == 4 %}
    {% break %}
  {% else %}
    {{ i }}
  {% endif %}
{% endfor %}



Output

1 2 3

Filters
abs
append
at_least
at_most
capitalize
ceil
compact
concat
date
default
divided_by
downcase
escape
escape_once
first
floor
join
last
lstrip
map
minus
modulo
newline_to_br
plus
prepend
remove
remove_first
replace
replace_first
reverse
round
rstrip
size
slice
sort
sort_natural
split
strip
strip_html
strip_newlines
times
truncate
truncatewords
uniq
upcase
url_decode
url_encode
where

x-----------------x---------------x-------------x---------------x---------------x