---
layout: post
title: 'Key-Value Data Store in iCloud'
---
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/apple/icloud-stainless-3-devices-key-value.png" alt="" width="275" align="right" />Apple's new <a title="iCloud platform" href="http://www.apple.com/icloud/">iCloud platform</a> includes a new <a class="zem_slink" title="Associative array" rel="wikipedia" href="http://en.wikipedia.org/wiki/Associative_array">key-value data</a> store, along side its <a title="document storage" href="http://www.kinlane.com/2011/06/document-management-in-icloud/">document storage</a>.<p></p>
An application can use the key-value data store to put small amounts of data in the cloud, and share with other instances of the same application running on other computers and IOS devices.<p></p>
The key-value data store is meant to save simple data types (numbers, strings, dates, and arrays) persistently and retrieve later.<p></p>
The amount of available space in a single key-value store is limited to 64 KB and the data for a single key cannot exceed 4 KB. This size allows the storage of small details from an application, but should not be used to store user documents or other large data objects, this should be done with <a title="iCloud document storage" href="http://blog.apievangelist.com/2011/06/08/icloud-storage-apis/">iCloud document storage</a>.<p></p>
Before an application can have access to a users key-value data stores it must request specific entitlements, in order to use iCloud storage.  This ensures a user has control over what gets stored in their iCloud account.<p></p>
The container identifier string must be of the form &lt;TEAM_ID&gt;.&lt;CUSTOM_STRING&gt;, where &lt;TEAM_ID&gt; is the unique ten-character identifier associated with an application developer account. The contents of &lt;CUSTOM_STRING&gt; can be anything that makes sense to your application. You can even use the same container identifier string for multiple applications if you want them to share the same storage space.<p></p>
The value of the container identifiers key is an array of strings. The first string in this array must be the main container identifier to associate with the application. Companies that develop multiple applications, can include additional container identifiers.<p></p>
Some examples of key-value usage might be, storing the current page or section of an application, so when the user returns to the applicaiton on same device or other devices, it opens to that same page and section.<p></p>
iCloud key-value storage is meant to empower developers with a centralize storage to use between devices, that enhances the user experience on Mac and iOS devices.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/06/08/icloud-storage-apis/">iCloud Storage APIs</a> (apievangelist.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/06/06/apple-icloud-api/">Apple iCloud API</a> (apievangelist.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/06/document-management-in-icloud/">Document Management in iCloud</a> (kinlane.com)</li>
</ul>
