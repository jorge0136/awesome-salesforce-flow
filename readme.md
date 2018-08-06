[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Useful resources for creating apps with [Salesforce Flow](https://www.youtube.com/watch?v=W8BJ4yRBga0&feature=youtu.be)

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. You might also like to read complete [awesome-list](https://github.com/sindresorhus/awesome).*

## 101, for those new to flow:

* [Automation Champion's how to series](https://automationchampion.com/learning-flow/)- 50 + examples of flow, this is a veritable garden of flow examples. Exceedingly well documented and explained, a great place to start. 
* [Additional 101 links](https://sites.google.com/view/flowunofficial/tutorials-and-beginner-material) - A long list of 101 resources. 
* [Learning flow](https://developingflow.com/learning-flow/)- Blog with a collection of 101 posts. 
* [Limits impacting flow](https://dreamevent.secure.force.com/articleView?id=vpm_admin_flow_limits.htm&type=5)

## Debugging/ error handling

* Native Tools: 
  * [New `debug` button](https://automationchampion.com/2018/05/22/getting-started-with-visual-workflow-part-7-learn-about-the-new-built-in-debug-tool-in-the-cloud-flow-designer/)
  * [Debug Log](https://unhandledsunshine.com/2018/01/21/salesforce-automation-what-is-going-on-in-there/)- In some cases, tried and true debug logging is the best tool for the job. 

* Other techniques:
  * [Flow Logging by Azimuth DS](https://appexchange.salesforce.com/listingDetail?listingId=a0N3A00000EFp89UAD)
  * [Flow Logging](https://www.clintmajors.com/blog/2018/3/6/flow-logging)- Tutorial describing how to show who is firing flows and what behaviour is being triggered when they run. 
  * [Handling the “Unhandled Fault” in Flow](https://salesforcedude.wordpress.com/2015/02/10/handling-the-unhandled-fault-in-flow/)- This one is critical, understanding this technique will improve a users experince greatly. 
  * [Which process failed?](https://www.linkedin.com/pulse/ways-identify-your-failed-flowprocess-builder-sudhir-kumar/)
  * [Flow error handling utility built in flow](https://explorationsintosalesforce.wordpress.com/2017/10/18/visual-flow-error-handling-utility-flows/)- This is an interesting technique, use it as inspiration when deciding how to handle your own errors.

## 201, for the advanced practioniners:

* [Flow auto bulkification](https://help.salesforce.com/articleView?id=vpm_admin_bulkification.htm&type=5) - Flow will auto bulkify certain actions in flow, you may want to read this one a few times. 
* [Size of collection variables](https://jenwlee.wordpress.com/2018/06/26/blink-you-may-have-missed-this-hidden-gem-get-count-via-flow-assignment/) - AKA why you no longer need to count in a loop
* [Pure function flows](https://explorationsintosalesforce.wordpress.com/2017/10/17/calling-subflows-that-do-not-need-input/)
* [Other flow tips and tricks](https://explorationsintosalesforce.wordpress.com/category/flow-tips-tricks/)
* [Example flows](https://sites.google.com/view/flowunofficial/flows)
* [Direct data queries within a flow](https://www.youtube.com/watch?v=Mon6OF_rtfo&feature=youtu.be) - This seems to be the future of flow, it is becoming more and more powerful. 

## Best practices:

* [Flow vs. Process Builder](https://www.adminhero.com/automation-showdown-process-builder-vs-workflow/)- This article explores when to use a process builder and when to use a flow. 
* [Platform event considerations](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_process_considerations.htm)- Suggestions for how to best play with platform events.
* [Don't do it all in one flow](https://jenwlee.wordpress.com/2016/10/11/maximize-maintainability-with-process-builder-and-componentized-visual-workflow/) - Modularize your flows. 
* [5 best practices](http://succeedwithsalesforce.com/5-best-practices-that-must-be-followed-when-building-flows/) 
* [As always, use validation rules](https://salesforcesidekick.com/2015/07/17/validation-rules-in-flow/)
* [Another take on validation rules](https://automationchampion.com/tag/validation-rule-in-flow/)
* [Don't hardcode, make it dynamic!](https://jenwlee.wordpress.com/2017/03/28/did-i-just-see-you-hardcode-a-salesforce-id-aw-hell-no/)

* Process builder best practices related to flow:  
  * [Consider using invokable processes with your flows](https://help.salesforce.com/articleView?id=process_advanced_invocable.htm&type=5)- Flows are very often fired from within a Process Builder, consider what logic should belong where. 
  * [Optimum performance in process builders](https://salesforcesidekick.com/2016/05/09/building-your-process-builder-for-optimum-performance-and-bulkification/)

## Testing/ Development lifecycle hacks:

* [Load your test data via a CSV](http://www.snugsfbay.com/2016/07/what-load-of-business-data.html)- This is a neat trick to make it easier to maintain valid test data. 
* [Pluralsight course on unit testing for admins](https://app.pluralsight.com/library/courses/salesforce-admin-essential-testing-techniques/table-of-contents) - Google for a free trial to plural sight. 
* [How I Learned to Stop Worrying and Test My Flow](https://salesforceyoda.com/2014/05/06/how-i-learned-to-stop-worrying-and-test-my-flow/)- Older blog post that still holds a few useful tips and tricks. 
* [Don't activate that flow](https://jenwlee.wordpress.com/2018/07/31/flow-tip-got-too-many-flow-versions/)- Blog explaining how in certain circumstances one can avoid activating a flow, creating another version. 

## Flow Libraries: 

* [Process Builder Blocks](https://github.com/mshanemc/processBuilderBlocks)- Quickly delete, manually share and complete other actions with these chunks of apex.
* [Salesforce Flow Utilities Library](https://github.com/thebrettbarlow/FlowUtilities)- Want to dedupe a string collection, remove oxford commas or manage multiple record types? This is the lib for you. 

* [Mass action scheduler](https://douglascayers.com/2017/12/25/mass-action-scheduler/)- Allows one to schedule flows to run at particular time.
* [Lightning Flow Components](https://github.com/alexed1/LightningFlowComponents)- Alex Edelstien's inventive flow components. See his [youtube](https://www.youtube.com/user/alexed100/videos) for demonstrations. See this [documentation](https://sites.google.com/view/flowunofficial/flow-screen-components) for further details.
* [Amazon Echo Skill for Salesforce Flow](https://github.com/financialforcedev/alexa-salesforce-flow-skill)
* [Dynamic Flow Component](https://andyinthecloud.com/2017/12/10/introducing-the-dynamic-flow-component/)- Define rules to have a flow fire inside of the lightning utility bar. This is one of the more exciting developments in flow in the recent past, be sure to take a look. 

## UI: 

* [Partial page update in flow](https://medium.com/@alexedelstein/the-update-screen-flow-action-component-2738e55498ff)- Allows one to update details on a page that have been edited by a flow without a full page refresh.
* [Different take on keeping data in sync](https://douglascayers.com/2017/09/12/keep-flows-and-data-in-sync-on-lightning-record-pages-winter-18/)

* Lightning: 
  * [Replace the Whole Flow Screen with Lightning Components](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/components_config_for_flow_screens_replace.htm)- Now that you can hide the default header and footer in a flow screen, you can fully customize your user's experience.
  * [creating-lightning-components-for-flow-screens](https://terencechiu.com/2018/06/13/creating-lightning-components-for-flow-screens/)
  * [Lightning components in flow](https://developingflow.com/2018/06/11/lightning-components-in-flow/)
  * [Trailheadx session on lightning flow](https://developer.salesforce.com/blogs/2018/06/icymi-trailheadx18-4-session-videos-about-process-automation.html)

## Updates: 

* Spring 18' 
    * [Dynamic Flow invocation from Apex](https://developer.salesforce.com/blogs/2018/04/adding-clicks-not-code-extensibility-to-your-apex-with-lightning-flow.html)- Powerful new features for invoking flows via apex. Adds mocking/ testing features in to test flow involved apex. Interesting examples of firing different flows based on custom metadata, which can be managed by an admin. 
    * [Flow local actions](http://releasenotes.docs.salesforce.com/en-us/spring18/release-notes/rn_forcecom_flow_localaction.htm)- With flow local actions, you can call the JavaScript controller of an associated Lightning component, which means you can integrate directly with the browser. 
* Summer 18' 
    * [Cloud Flow Design Guide](http://resources.docs.salesforce.com/214/11/en-us/sfdc/pdf/salesforce_vpm_implementation_guide.pdf)
    * [What changed in flow this update?](https://releasenotes.docs.salesforce.com/en-us/summer18/release-notes/rn_forcecom_flow_design.htm)

## What makes for an awesome list?
Read [the awesome manifesto](https://github.com/mailtoharshit/awesome-salesforce/blob/master/contributing.md) and see if your list complies.

  Read Related Awesome Pages :
  * [Awesome Salesforce](https://github.com/mailtoharshit/awesome-salesforce)
   * [Awesome Lighting](https://github.com/mailtoharshit/awesome-lighting)
   * [Awesome Salesforce Articles](https://github.com/mailtoharshit/awesome-salesforce-articles)
   * [Awesome Browser Extensions](https://github.com/mailtoharshit/awesome-browser-extensions-for-salesforce/blob/master/README.md)
   * [Awesome Heroku](https://github.com/mailtoharshit/awesome-heroku)