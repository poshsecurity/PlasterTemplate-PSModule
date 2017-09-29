# Contributing

I always love to have contributions to any of my modules!

## Issues

If you find an issue, or want to request a new feature, start by looking at the Issues within GitHub. 

When you create a new issue in the tracker, please follow these recommendations:

* Issues should be actionable, i.e., fixable.
* Use a descriptive title that describes the issue you have encountered or the feature you want added.
* Be as detailed as possible, it is safe to say that more is usually better.
* For bug reports, I recommend:
    * Describe what you were doing, with as much possible, include screenshots where possible.
    * Describe what you expected and what actually happend.
    * Provide the code or steps you followed to produce the issue. It is hard/impossible to fix an issue that cannot be reproduced.
    * Don't be affraid to include PowerShell transcripts.
    * Include all possible expcetion messages and strack traces. Where possible include the ```ScriptStackTrace``` and any other PowerShell error properties.
    * If there is private/confidential information, feel free to remove that from any logs/transcripts/images, but remember to highlight where you have done so.
* If you do raise an issue, please ensure that you subscribe to notifications for the create issue in case there are any follow-up questions, and to assist in testing.

## Pull Requests

Pull requests are always more than welcome. Here are a few guidelines that should be followed:

* Each pull request should accomplish a clear goal. Ensure that you clearly state in the request what it accomplishes.
    * Big fixes: What was the bug? How did you fix it?
    * New features: What is it? How is it used?
* Provide a high level explanation of what you are changing, it makes it easier to review.
* Keep requests small, as it:
    * Makes reviews easier.
    * Makes testing easier.
    * Helps review conflicts more easily.
* Ensure that all Pester tests pass and there are no failures.
* Ensure that there are no errors or warnings with PowerShell Script Analyzer
* Any new code needs to have tests created:
    * Bug fixes: Consider test cases that would have failed before the change but pass now.
    * New features: Test cases need to ensure that new features function correctly and existing features still function as previously expected.
* Ensure that any code you write aligns with community style guides.
