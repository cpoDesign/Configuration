# Configuration
Contains custom snippets and config files in improve development
# Resharper
##  ValidFromTo template for lambda extension
 Lambda expression that adds validation on date if defined or out of valid range
 
 $pp$.$ValidFromDate$ < DateTime.Now && ($pp$.$ValidToDate$ == null || $pp$.$ValidToDate$.Value > DateTime.Now)
