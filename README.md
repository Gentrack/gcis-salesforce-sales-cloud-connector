### Event Publisher and Triggers

With the platform event created the next step is to intercept various internal events and publish them out for the connector to receive:

1. [Add a new Apex class](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_qs_class.htm) called GentrackCallout, referring to [GentrackCallout.apxc](GentrackCallout.apxc) sample code on this repository for an example on how to implement.
2. [Add a new Apex class](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_qs_class.htm) called TriggerHandler, referring to [TriggerHandler.apxc](TriggerHandler.apxc) sample code on this repository for an example on how to implement.
3. [Add a new Apex trigger](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_qs_trigger.htm) called AccountTrigger, referring to [AccountTrigger.apxt](apex-triggers/AccountTrigger.apxt) sample code on this repository for an example on how to implement.
4. [Add a new Apex trigger](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_qs_trigger.htm) called ContactTrigger, referring to [ContactTrigger.apxt](apex-triggers/ContactTrigger.apxt) on this repository for an example on how to implement.
5. [Add a new Apex trigger](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_qs_trigger.htm) called AccountContactRelation, referring to [AccountContactRelation.apxt](apex-triggers/AccountContactRelation.apxt) on this repository for an example on how to implement.

We recommend you follow your normal Salesforce code release process in writing, testing, and deploying these classes and triggers. You may also consider alternative designs depending other Apex code you have running in your instance.