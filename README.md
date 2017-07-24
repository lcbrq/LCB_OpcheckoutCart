# LCB_OpcheckoutCart

Add Magento cart to the Uni Express Checkout 

## Usage

Add following line to your opcheckout.xml reference name content layout declaration

<block type="opcheckoutcart/index" name="opcheckoutcart_index" as="opcheckoutcart" template="opcheckoutcart/index.phtml"/>

and insert 

```php
<?php echo $this->getChildHtml('opcheckoutcart'); ?> inside openepage.phtml

