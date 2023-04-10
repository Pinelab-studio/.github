# How to contribute to Pinelab's projects?

Contribution's are always welcome! Just:

* [Fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo) you'd like to contribute to
* [Create a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) for your changes against the original repository

## Coding guidelines

To keep code quality high and maintainable, we've set up a few guidelines to help you :sparkles: 

* **Automated tools** - We rely heavily on automated tools to keep our projects maintainable, so please make sure you've added test cases if necessary and linted your code.
* **Logging** - Only log errors if it's actually an error: An errors is something needs to be fixed by a developer.

    - These should be `warnings`, not errors: Bad user input. Bad config that can be solved by changing settings via a UI.
    - These are actual `errors`: A request failed. An async job failed after it's max retries.   

(This document is still a work in progress...)