# Magento1.9-CatalogPriceRulesFix
Catalog price rules core bug in Magento CE 1.9.1 and EE 1.14.1.0 (Array to string conversion error and incorrect price rules behavior)

Short summary of the problem – if you have Magento catalog price rules with multiple select attributes in conditions 
or ONE OF price rules conditions with comma separated values - on latest Magento versions – 
you can have Array to string conversion error during you apply rules or incorrect rules behavior.

Issue reports:
- http://magento.stackexchange.com/questions/36195/catalog-price-rule-containing-several-sku-s-doesnt-work
- http://www.magentocommerce.com/bug-tracking/issue/index/id/278	
- http://www.magentocommerce.com/bug-tracking/issue/index/id/544 	
