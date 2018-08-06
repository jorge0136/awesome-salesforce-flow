## 101, for those new to flow:
* [Automation Champion's how to series](https://automationchampion.com/learning-flow/)- 50 + examples of flow, this is a veritable garden of flow examples. Exceedingly well documented and explained, a great place to start. 
* [Learning flow](https://developingflow.com/learning-flow/)- Additional flow how to blogs. 
* [Limits impacting flow](https://dreamevent.secure.force.com/articleView?id=vpm_admin_flow_limits.htm&type=5)



## Library
    ### Invocable Apex: 
        * [Process Builder Blocks](https://github.com/mshanemc/processBuilderBlocks)- Quickly delete, manually share and complete other actions with these chunks of apex.
        * [Salesforce Flow Utilities Library](https://github.com/thebrettbarlow/FlowUtilities)- Want to dedupe a string collection, remove oxford commas or manage multiple record types? This is the lib for you. 
* [Mass action scheduler](https://douglascayers.com/2017/12/25/mass-action-scheduler/)- Allows one to schedule flows to run at particular time.
* [Lightning Flow Components](https://github.com/alexed1/LightningFlowComponents)- Alex Edelstien's inventive flow components. See his [youtube](https://www.youtube.com/user/alexed100/videos) for demonstrations. See this [documentation](https://sites.google.com/view/flowunofficial/flow-screen-components) for further details.
* [Different logging library](https://appexchange.salesforce.com/listingDetail?listingId=a0N3A00000EFp89UAD)
* [Amazon Echo Skill for Salesforce Flow](https://github.com/financialforcedev/alexa-salesforce-flow-skill)
* [Dynamic Flow Component](https://andyinthecloud.com/2017/12/10/introducing-the-dynamic-flow-component/)- Define rules to have a flow fire inside of the lightning utility bar. This is one of the more exciting developments in flow in the recent past, be sure to take a look. 

## Debugging/ error handling

### Native Tools: 
  * [New `debug` button](https://automationchampion.com/2018/05/22/getting-started-with-visual-workflow-part-7-learn-about-the-new-built-in-debug-tool-in-the-cloud-flow-designer/)
  * [Debug Log](https://unhandledsunshine.com/2018/01/21/salesforce-automation-what-is-going-on-in-there/)- In some cases, the new debug feature is not sufficient, in which case, tried and true debug logging can be your friend.

### Other techniques: 
* [Flow Logging](https://www.clintmajors.com/blog/2018/3/6/flow-logging)- Tutorial describing how to show who is firing flows and what behaviour is being triggered when they run. 
* [Handling the “Unhandled Fault” in Flow](https://salesforcedude.wordpress.com/2015/02/10/handling-the-unhandled-fault-in-flow/)- This one is critical, understanding this technique will improve a users experince greatly. 
* [Which process failed?](https://www.linkedin.com/pulse/ways-identify-your-failed-flowprocess-builder-sudhir-kumar/)
* [Flow error handling utility built in flow](https://explorationsintosalesforce.wordpress.com/2017/10/18/visual-flow-error-handling-utility-flows/)- This is an interesting technique, use it as inspiration when deciding how to handle your own errors.
* [Additional 101 links](https://sites.google.com/view/flowunofficial/tutorials-and-beginner-material)




## 201, for the advancded practioniners: 
* [Flow auto bulkification]https://help.salesforce.com/articleView?id=vpm_admin_bulkification.htm&type=5- Flow will auto bulkify certain actions in flow, you may want to read this one a few times. 
* [Size of collection variables, AKA why you no longer need to count in a loop](https://jenwlee.wordpress.com/2018/06/26/blink-you-may-have-missed-this-hidden-gem-get-count-via-flow-assignment/)
* [Pure function flows](https://explorationsintosalesforce.wordpress.com/2017/10/17/calling-subflows-that-do-not-need-input/)
* [Other flow tips and tricks](https://explorationsintosalesforce.wordpress.com/category/flow-tips-tricks/)

## Best practices:

* [Flow vs. Process Builder](https://www.adminhero.com/automation-showdown-process-builder-vs-workflow/)- This article explores when to use a process builder and when to use a flow. 
* [Platform event considerations](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_process_considerations.htm)- Suggestions for how to best play with platform events.
* [Don't do it all in one flow](https://jenwlee.wordpress.com/2016/10/11/maximize-maintainability-with-process-builder-and-componentized-visual-workflow/)
* [5 best practices](http://succeedwithsalesforce.com/5-best-practices-that-must-be-followed-when-building-flows/)
* [As always, use validation rules](https://salesforcesidekick.com/2015/07/17/validation-rules-in-flow/)
* [Another take on validation rules](https://automationchampion.com/tag/validation-rule-in-flow/)
* [Don't hardcode, make it dynamic!](https://jenwlee.wordpress.com/2017/03/28/did-i-just-see-you-hardcode-a-salesforce-id-aw-hell-no/)

### Process builder best practices related to flow:  

* [Consider using invokable processes with your flows](https://help.salesforce.com/articleView?id=process_advanced_invocable.htm&type=5)- Flows are very often fired from within a Process Builder, consider what logic should belong where. 
* [Optimum performance in process builders](https://salesforcesidekick.com/2016/05/09/building-your-process-builder-for-optimum-performance-and-bulkification/)




## Testing/ Development lifecycle hacks: 
* [Load your test data via a CSV](http://www.snugsfbay.com/2016/07/what-load-of-business-data.html)- This is a neat trick to make it easier to maintain valid test data. 
* [Pluralsight course on unit testing for admins](https://app.pluralsight.com/library/courses/salesforce-admin-essential-testing-techniques/table-of-contents)
* [How I Learned to Stop Worrying and Test My Flow](https://salesforceyoda.com/2014/05/06/how-i-learned-to-stop-worrying-and-test-my-flow/)- Older blog post that still holds a few useful tips and tricks. 
* [Don't activate that flow](https://jenwlee.wordpress.com/2018/07/31/flow-tip-got-too-many-flow-versions/)- Blog explaining how in certain circumstances one can avoid activating a flow, creating another version. 

## UI: 

* [Partial page update in flow](https://medium.com/@alexedelstein/the-update-screen-flow-action-component-2738e55498ff)- Allows one to update details on a page that have been edited by a flow without a full page refresh. 

    ### Lightning: 
    * [Replace the Whole Flow Screen with Lightning Components](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/components_config_for_flow_screens_replace.htm)- Now that you can hide the default header and footer in a flow screen, you can fully customize your user's experience.

## Updates: 
* Spring 18' 
    * [Dynamic Flow invocation from Apex](https://developer.salesforce.com/blogs/2018/04/adding-clicks-not-code-extensibility-to-your-apex-with-lightning-flow.html)- Powerful new features for invoking flows via apex. Adds mocking/ testing features in to test flow involved apex. Interesting examples of firing different flows based on custom metadata, which can be managed by an admin. 
    * [Flow local actions](http://releasenotes.docs.salesforce.com/en-us/spring18/release-notes/rn_forcecom_flow_localaction.htm)- With flow local actions, you can call the JavaScript controller of an associated Lightning component, which means you can integrate directly with the browser. 
* Summer 18' 
    * [Cloud Flow Design Guide](http://resources.docs.salesforce.com/214/11/en-us/sfdc/pdf/salesforce_vpm_implementation_guide.pdf)
    * [What changed in flow this update?](https://releasenotes.docs.salesforce.com/en-us/summer18/release-notes/rn_forcecom_flow_design.htm)