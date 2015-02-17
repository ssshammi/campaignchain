Changelog for CampaignChain Community Edition 1.0.0-beta
========================================================

This changelog references the relevant changes done in 1.0.0-beta.x releases.

Find details about the issues here: https://campaignchain.atlassian.net


1.0.0-beta.1 (2015-02-17)
-------------------------

* Bug

    * [CE-200] - Timeline: Today line to long at bottom in embedded view, breaks sync with left column
    * [CE-243] - Module installer to also take into account modules in src/
    * [CE-251] - Error when providing correct channel for activity module generation
    * [CE-252] - Update auto-generated stub entries in campaignchain.yml
    * [CE-253] - Use vendor name as prefix of module name in campaignchain.yml
    * [CE-254] - Add mandatory routes automatically in campaignchain.yml and routing.yml
    * [CE-260] - Compile Error: Cannot redeclare class OAuthSignatureMethod_HMAC_SHA1
    * [CE-274] - Operation's CSS should include suffix
    * [CE-277] - Ask for required website link to specify homepage in composer.json
    * [CE-278] - Controller of Activity module should not be empty
    * [CE-282] - DataTables boostrap JS asset does not exist
    * [CE-289] - module description vs. display name
    * [CE-290] - Index route and Controller in report module
    * [CE-291] - Allow vendor name to be CamelCase

* Improvement

    * [CE-242] - Extend campaignchain:module:update to completely update modules registry
    * [CE-249] - Show just Channel icon if Location has no image
    * [CE-250] - Compose channel icon per channel module
    * [CE-259] - Use trigger hook tpl in Activity sidebar and report
    * [CE-261] - Create route entries for Activity module
    * [CE-263] - Generate report stubs for Operation module
    * [CE-264] - Generate form type and templates and CSS for Operation
    * [CE-268] - Verify in modules installer, that required routes have been provided by Channel, Activity, Campaign, Milestone modules
    * [CE-270] - Store bundle class when registering it and use this to compose the Web assets path
    * [CE-275] - Ask for Metrics of an Operation module
    * [CE-276] - Describe syntax of channel for Activity module
    * [CE-279] - Include Hooks for Activity module
    * [CE-280] - Change "Module license" to "Package license"
    * [CE-281] - Generate Channel module controller
    * [CE-288] - module name should be allowed to have dashes

* New Feature

    * [CE-240] - Integrate with GoToWebinar
    * [CE-245] - Visualize CTA tracking
    * [CE-273] - Create entity skeleton per operation module

* Task

    * [CE-246] - Date and time format in user profile should not be editable