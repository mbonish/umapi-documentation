---
layout: page
title: User Management API Documentation
nav_link: UMAPI
nav_level: 1
nav_order: 15
lang: en
---

Welcome to the documentation center for User Management APIs from Adobe.  

News:  
<hr class="api-ref-rule">
<div class="isa_info">
<p>Since June 8th 2020, the page size for APIs relating to the retrieval of users has been increased from 400 to 1000. No changes are required by existing clients.</p>
<hr class="api-ref-rule">
<p>Starting March 10th 2020, new property <code>groupId</code> will be returned as part of the response for retrieving groups and products. Clients are not impacted by this change.</p>
<hr class="api-ref-rule">
<p>Since February 11th 2020, the page size for APIs relating to the retrieval of groups has been increased from 200 to 400. No changes are required by existing clients.</p>
<hr class="api-ref-rule">
<p>Starting August 8th 2019, a change is applied to align with the multiple domains per directory model and tightening the security of the <strong>create</strong> and <strong>update</strong> APIs.</p>
<p>As a result, any application using the <strong>create</strong> or <strong>update</strong> API statements using domains for which there's no claim in Admin Console, will start failing.</p>
<hr class="api-ref-rule">
<p>On April 2nd, 2019, Creative Cloud product names will remove the “CC”. For example, “Photoshop CC” will be renamed “Photoshop”.</p>
<p>As a result, any application directly accessing the User Management API which include logic <strong>dependent on the product name</strong> will need to be updated. If you have not included the product name in the code, then this will not impact your connection to the User Management API. If you use the User Sync Tool, you should see no impact.</p>
<p>Note: the term “CC” included in the name of a Product Profile <em>will not change</em>. If you rely on the name of the “product admin group” (e.g., <code>_admin_&lt;product name&gt;</code>) you may be impacted and have to update your scripts.</p>
<p>As a best practice, it is recommended to avoid any logic that expects fixed product names.</p>
</div>



[Getting Started with User Management](getstarted.md)

[User Management API Overview](API_introduction.md)

[User Management API Reference](RefOverview.md)

[User Management Walkthrough](samples/index.md)
