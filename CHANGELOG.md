# Changelog
## 1.1.1
New configuration props:
* **onChangeText** - Method triggered when TextInput is changed. Returning query and this.
## 1.1.0
New configuration props:
* **querySession** - A random string which identifies an autocomplete session for billing purposes. If this parameter is omitted from an autocomplete request, the request is billed independently. See the pricing sheet for details.
## 1.0.10
New configuration props:
* **queryTypes** - You may restrict results from a Place Autocomplete request to be of a certain type by passing a types parameter.
## 1.0.9
Fixing an issue with sometimes not getting details about selected place.
## 1.0.8
Fixed issue that in some cases list of places is not displayed. 
## 1.0.7
Fixed issue in Android with TouchOpacity not clickable in Scroll View with absolute position.
## 1.0.6
Bug fixes:
* Component wont trigger search if input value is empty or after you clear it using text input x

New configuration props:
* **requiredCharactersBeforeSearch** - component wont fetch places unless string length is equal this prop. Default 2.
* **requiredTimeBeforeSearch** - idle time on text input before component will fetch places.
## 1.0.5
Remove default props for lat,lng and radius. 
Add queryCountries where you can pass array of countries to limit your search results. 
## 1.0.4
Update changelog and readme
## 1.0.3
Set Text Input value based on selected place.
