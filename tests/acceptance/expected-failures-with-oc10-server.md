## Scenarios from web tests that are expected to fail on oC10

Lines that contain a format like "[someSuite.someFeature.feature:n](https://github.com/owncloud/web/path/to/feature)"
are lines that document a specific expected failure. Follow that with a URL to the line in the feature file in GitHub.
Please follow this format for the actual expected failures.

Level-3 headings should be used for the references to the relevant issues. Include the issue title with a link to the issue in GitHub.

Other free text and markdown formatting can be used elsewhere in the document if needed. But if you want to explain something about the issue, then please post that in the issue itself.

### [Media Viewer](https://github.com/owncloud/ocis/issues/1106)
-   [webUIPreview/imageMediaViewer.feature:81](https://github.com/owncloud/web/blob/master/tests/acceptance/features/webUIPreview/imageMediaViewer.feature#L81)
-   [webUIPreview/imageMediaViewer.feature:88](https://github.com/owncloud/web/blob/master/tests/acceptance/features/webUIPreview/imageMediaViewer.feature#L88)

### [WebUI Login](https://github.com/owncloud/web/issues/4564)
-   [webUILogin/login.feature:62](https://github.com/owncloud/web/blob/master/tests/acceptance/features/webUILogin/login.feature#L62)
