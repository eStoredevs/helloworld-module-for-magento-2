# helloworld-module-for-magento-2

<h2> Mannual Installation Instructions 
<a href="http://www.estoredevs.com/magento-2-extensions/featured-product-for-magneto2.html">More Info</a></h2> 
go to Magento2Project root dir 
place the plugin under following Directory  :<br/>
<strong>/Magento2Project/app/code/</strong>


<h3> Enable Estdevs/Featuredproduct Module</h3>
to Enable this module you need to follow these steps:

<ul>
<li>
<strong>Enable the Module</strong>
<pre>bin/magento module:enable Estdevs_Helloworld</pre></li>
<li>
<strong>Run Upgrade Setup</strong>
<pre>bin/magento setup:upgrade</pre></li>
<li>
<strong>Re-Compile (in-case you have compilation enabled)</strong>
	<pre>bin/magento setup:di:compile</pre>
</li>
</ul>
