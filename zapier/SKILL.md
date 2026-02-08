---
name: zapier
description: 
metadata:
  source: llms.txt
  source_url: https://docs.zapier.com/llms.txt
  generated: 2026-02-08T17:02:57.449Z
---

# Zapier

## Available Resources

### Docs

- **null**
  - URL: https://docs.zapier.com/CLAUDE.md

- **Zapier Docs**
  - URL: https://docs.zapier.com/index.md

- **null**
  - URL: https://docs.zapier.com/mcp/clients.md

- **Submit an issue**
  - URL: https://docs.zapier.com/mcp/help/bug.md

- **Chatbot Helper**
  - URL: https://docs.zapier.com/mcp/help/chat-bot.md

- **Join our Community**
  - URL: https://docs.zapier.com/mcp/help/community.md

- **Enterprise Access**
  - URL: https://docs.zapier.com/mcp/help/enterprise-access.md

- **null**
  - URL: https://docs.zapier.com/mcp/home.md

- **Quickstart**: Get up and running with Zapier MCP in 5 minutes
  - URL: https://docs.zapier.com/mcp/quickstart.md

- **Usage & Billing Overview**: Understand how Zapier MCP usage works, rate limits, and pricing during beta
  - URL: https://docs.zapier.com/mcp/usage/overview.md

- **Core reference**: Reference for `zapier-platform-core`
  - URL: https://docs.zapier.com/platform/build-cli/core.md

- **Download the source code of a CLI integration**: If at any point you do not have the source code for your CLI integration and need it to make changes, you can download a zip file of the source code directly from the Platform UI.
  - URL: https://docs.zapier.com/platform/build-cli/download-source-code.md

- **Dynamic dropdowns**
  - URL: https://docs.zapier.com/platform/build-cli/dynamic-dropdowns.md

- **Empty values in input data**: Handing empty values in `bundle.inputData` in your `perform*` functions
  - URL: https://docs.zapier.com/platform/build-cli/empty-values-in-input-data.md

- **Frequently Asked Questions**
  - URL: https://docs.zapier.com/platform/build-cli/faqs.md

- **Hydration**: The best answer to this lives in our [CLI docs](https://docs.zapier.com/platform/reference/cli-docs#dehydration):
  - URL: https://docs.zapier.com/platform/build-cli/hydration.md

- **Unauthorized Access to Zapier NPM Packages**
  - URL: https://docs.zapier.com/platform/build-cli/inc-547.md

- **Input Field Configuration**
  - URL: https://docs.zapier.com/platform/build-cli/input-fields.md

- **Making HTTP requests**: How to make HTTP requests from your Zapier integration to interact with your API
  - URL: https://docs.zapier.com/platform/build-cli/making-http-requests.md

- **Build with CLI**: Zapier is a platform for creating integrations and workflows. This CLI is your gateway to creating custom applications on the Zapier platform.
  - URL: https://docs.zapier.com/platform/build-cli/overview.md

- **Testing and debugging**: Test your integration using `invoke` command and unit tests. Debug locally using a step-by-step debugger.
  - URL: https://docs.zapier.com/platform/build-cli/testing-and-debugging.md

- **TypeScript integrations**: TypeScript is a first-class language for building integrations with the CLI.
  - URL: https://docs.zapier.com/platform/build-cli/typescript-integrations.md

- **Action**: Every Zap starts with a single trigger that watches for new or updated data, starting the user's workflow. Action steps then make use of that data.
  - URL: https://docs.zapier.com/platform/build/action.md

- **Add input fields to triggers and actions**: When building in the Platform UI, you'll use the Input Designer to create the form users will input data into, to send to your app's API.
  - URL: https://docs.zapier.com/platform/build/add-fields.md

- **Add authentication with API Key**: API Key authentication passes along a user-entered API Key with every API call. In your Zapier integration using API Key authentication, the API key—and optionally any other data your API needs—is included every time a Zap step runs.
  - URL: https://docs.zapier.com/platform/build/apikeyauth.md

- **Authentication**: Connecting an app to Zapier starts with authentication. Users select an app they wish to use in their Zap, authenticating their account with that app to allow Zapier to access their data.
  - URL: https://docs.zapier.com/platform/build/auth.md

- **Add authentication with Basic Authentication**: APIs using Basic Authentication will authenticate users with a username and password. In your Zapier integration using Basic Auth, Zapier includes the username and password credentials in the API request bundle every time Zapier polls an API endpoint for new data or posts new data to an API endpoint.
  - URL: https://docs.zapier.com/platform/build/basicauth.md

- **Reference user-entered details with data bundles**: Zapier stores data from users' authentication and input forms for API calls in the `bundle` object. You can reference that data in your integration using either `{{bundle.bundleName.field}}` or `${bundle.bundleName.field}`, depending on the context. Replace `bundleName` with the bundle name and `field` with the input field key or API response field key you need.
  - URL: https://docs.zapier.com/platform/build/bundle.md

- **Add an instant trigger using REST Hooks in Zapier Platform CLI**: REST Hooks are an alternative to polling. The main differences are allowing your customers' Zaps to trigger instantly; and avoiding polling triggers' numerous - and sometimes unnecessary - requests to your API's endpoints to check for new data.
  - URL: https://docs.zapier.com/platform/build/cli-hook-trigger.md

- **Use Code Mode to refine your API call**
  - URL: https://docs.zapier.com/platform/build/code-mode.md

- **Use computed fields in OAuth or Session Authentication**: When adding a field in your integration's authentication configuration, Zapier offers two field type options; field and computed field. The field option allows users to enter account information needed for authentication.
  - URL: https://docs.zapier.com/platform/build/computed-fields.md

- **Compute a field from the data of the Test API call**: Zapier doesn't store the responses from the test API call for OAuth v2 and session authentication. Using computed fields, you can use data from a test API call later in your Zapier integration.
  - URL: https://docs.zapier.com/platform/build/computed-test-field.md

- **Add a connection label**: Zapier users can authenticate multiple accounts for any app. By default, every new app account added to Zapier is identified by the app's name, followed by a number (#2, #3, …) for accounts connected after the first.
  - URL: https://docs.zapier.com/platform/build/connection-label.md

- **Add a create action**
  - URL: https://docs.zapier.com/platform/build/create.md

- **How deduplication works in Zapier**: Zapier automatically deduplicates incoming trigger data for your integration, so that Zaps do not run multiple times on the same data. Consider the following requirements for your “New Item” and “Updated Item” triggers to work as users expect.
  - URL: https://docs.zapier.com/platform/build/deduplication.md

- **Add authentication with Digest Authentication**: Digest Auth prompts users to enter their username and password, optionally along with any additional data your API requires for authentication. Zapier makes an unauthenticated API call to get the nonce from your server, and uses it to encrypt and pass the authentication data to your server with each API call.
  - URL: https://docs.zapier.com/platform/build/digestauth.md

- **Send or receive dynamic user-defined fields through your API**: Dynamic fields are a type of field built from an API call. Custom code runs to show fields based on other input field data. These are especially useful with project management apps, CRM apps, databases, and any other app where users can add custom, user-defined fields.
  - URL: https://docs.zapier.com/platform/build/dynamic-field.md

- **Use environment variables in your API call**: Integrations can define environment variables that are available when the app's code executes. They are useful when you have data like an OAuth client ID and secret that you don't want to commit to source control. Environment variables can also be used as a way to toggle between a staging and production environment during app development and this would be recommended instead of the use of an independent integration for staging purposes.
  - URL: https://docs.zapier.com/platform/build/env.md

- **Error: An array is expected**: When you add a polling trigger or search action to your integration, the Zapier platform [expects a bare array of new or found items returned](/platform/build/response-types), sorted in reverse chronological order. An API may instead return a result _object_ that contains the array of items the trigger/search needs.
  - URL: https://docs.zapier.com/platform/build/error-array-expected.md

- **Error: Cannot retrieve App******CLIAPI@*** app**
  - URL: https://docs.zapier.com/platform/build/error-cannot-retrieve-app.md

- **Error: Got a non-object result, expected an object from create**
  - URL: https://docs.zapier.com/platform/build/error-non-object.md

- **Error: Got a non-object result in the array, expected only objects**: When using a REST Hook trigger, the data returned by the perform must be an array.
  - URL: https://docs.zapier.com/platform/build/error-non-object-array.md

- **Add error response handling**: If your API returns responses with a status code above 400 that should not automatically throw an error then Zapier recommends enabling skipThrowForStatus.
  - URL: https://docs.zapier.com/platform/build/errors.md

- **Field types**
  - URL: https://docs.zapier.com/platform/build/field-definitions.md

- **Use form mode to setup your API calls**: In the Platform UI, when building your authentication, triggers and actions, the default setting under _API Configuration_ is to create each component of your integration using Form Mode.
  - URL: https://docs.zapier.com/platform/build/form-mode.md

- **Add a REST Hook trigger**: Set up your REST Hook trigger in the Platform UI with the Settings, Input Designer and API Configuration tabs.
  - URL: https://docs.zapier.com/platform/build/hook-trigger.md

- **Hydration/dehydration limits**: [File dehydration](https://docs.zapier.com/platform/build-cli/overview#file-dehydration) is an extremely useful tool to remain within time and size constraints for Zapier triggers and actions. However, it does have its own limits.
  - URL: https://docs.zapier.com/platform/build/hydration-limits.md

- **Add line item group field to actions**: Input fields in Zapier add one item each time the Zap runs. But, if you want users to be able to add multiple items in a single Zap run, then this can be achieved by using a line item group. This group takes line items, which are comma-separated values, and adds each instance of the values to the app in a single Zap run.
  - URL: https://docs.zapier.com/platform/build/line-items.md

- **Add authentication with OAuth v2**: OAuth v2 authentication matches in appearance the login process users expect from most modern apps.
  - URL: https://docs.zapier.com/platform/build/oauth.md

- **Zapier operating constraints**: Zapier offers a relatively unique run-time environment for your integration and its requests to your API. The environment is stateless and restricts both execution time and payload size to offer normalized reliability and running time. There are three distinct contexts of this run-time that your integration will need to consider.
  - URL: https://docs.zapier.com/platform/build/operating-constraints.md

- **Use pagination in triggers**: By default, Zapier triggers fetch new or recently updated data to start Zaps, and only need to find the most recently added items. Triggers can also be used to populate [dynamic dropdown fields](/platform/build/add-fields#dynamic-dropdown), and there they need to find all possible items to populate the field.
  - URL: https://docs.zapier.com/platform/build/pagination-trigger.md

- **Add a polling trigger**: Set up your polling trigger in the Platform UI with the Settings, Input Designer and API Configuration tabs.
  - URL: https://docs.zapier.com/platform/build/polling-trigger.md

- **Reduce requests to your API**
  - URL: https://docs.zapier.com/platform/build/reduce-api-requests.md

- **Reorder or remove action**: Whenever a user selects your app's integration in a Zapier action step, they'll see every _create_ and _search_ action in your integration. 
  - URL: https://docs.zapier.com/platform/build/reorder-action.md

- **Reorder or remove triggers**: Triggers are listed in alphabetical order in the Zap editor and this order cannot be changed.
  - URL: https://docs.zapier.com/platform/build/reorder-trigger.md

- **Add authentication fields to Request Template**: The Request Template is a request editor that lets users set static values that apply to all requests made by this integration. Users can configure the URL params, HTTP headers and request body. This is the perfect place to set authentication fields.
  - URL: https://docs.zapier.com/platform/build/requesttemplate.md

- **Response types Zapier expects**: With every API call, Zapier expects the response data to be returned in a specific response type. This can vary depending on what part of your integration you're working on. Use the table below to identify the correct response type to use
  - URL: https://docs.zapier.com/platform/build/response-types.md

- **Output data, defining sample data and output fields**: This guide will explain what output data, sample data and output fields are and how to modify them in your triggers or actions.
  - URL: https://docs.zapier.com/platform/build/sample-data.md

- **Add a search action**
  - URL: https://docs.zapier.com/platform/build/search.md

- **Add a search or create action**: When adding a _search_ action type, you'll see the option to _Pair an existing search and a create to enable “Find or Create” functionality_ in the _Settings_ page. This embeds the _create_ inside the _search_ step to find or create items in one step of the Zap.
  - URL: https://docs.zapier.com/platform/build/search-or-create.md

- **Add authentication with Session Authentication**: Session authentication has elements of Basic authentication — where Zapier requests a username and password, and OAuth v2 — where Zapier redirects users to the app's site to allow access. User credentials are exchanged for a token used to authenticate subsequent API calls.
  - URL: https://docs.zapier.com/platform/build/sessionauth.md

- **Enable static IP address connection for customers**: To enable customers to access your integration by static IP address, all outbound traffic from Zapier to your integration will need to be routed through a smaller set of consistent IP addresses. Any app owner/developer can request to enable the static IP address feature on a private or public app.
  - URL: https://docs.zapier.com/platform/build/static-ip.md

- **Validate domain and subdomain input fields during authentication**: When adding a subdomain input field, commonly used in OAuth implementations, additional validation is strongly recommended to prevent a potential security vulnerability. If not taken into account, an attacker could utilize a maliciously constructed subdomain field (like `attacker-domain.com/`) in order to redirect OAuth connection requests to that attacker-controlled domain (because `attacker-domain.com/.your-domain.com` resolves to the attacker's domain instead of the expected one). Taking the following steps prevents the potential for an attacker to access your integration's sensitive authentication information, such as the OAuth client ID or secret.
  - URL: https://docs.zapier.com/platform/build/subdomain-validation.md

- **Test authentication**: Testing a user's authentication is crucially important, as it is later used to test subsequent trigger and action steps when built.
  - URL: https://docs.zapier.com/platform/build/test-auth.md

- **Test and monitor your integration in your Zapier account**: Testing inside the Platform UI is crucial during the building process. To ensure users can benefit from your integration's features, it is equally crucial to test your integration within the Zap editor. This is the best way to notice details that might have been overlooked while building your integration.
  - URL: https://docs.zapier.com/platform/build/test-monitoring.md

- **Testing Tools**: The Zapier platform provides a set of tools to help inform and validate your integration before pushing changes out to users.
  - URL: https://docs.zapier.com/platform/build/test-tools.md

- **Test triggers or actions**: Once authentication is tested, trigger and action steps are easy to test inside Zapier visual builder. Set up the trigger or action settings and API calls, then as the last step the familiar _Test Your API Response_ box appears. It will show any accounts you added to your integration previously during the authentication testing.
  - URL: https://docs.zapier.com/platform/build/test-triggers-actions.md

- **Trigger**
  - URL: https://docs.zapier.com/platform/build/trigger.md

- **Troubleshoot action request or response payload size**
  - URL: https://docs.zapier.com/platform/build/troubleshoot-action-payload.md

- **Troubleshoot action timeouts**
  - URL: https://docs.zapier.com/platform/build/troubleshoot-action-timeouts.md

- **Troubleshoot custom fields**
  - URL: https://docs.zapier.com/platform/build/troubleshoot-custom-fields.md

- **Troubleshoot throttles**
  - URL: https://docs.zapier.com/platform/build/troubleshoot-throttles.md

- **Troubleshoot trigger request or response payload sizes**
  - URL: https://docs.zapier.com/platform/build/troubleshoot-trigger-payload.md

- **Troubleshoot trigger timeouts**
  - URL: https://docs.zapier.com/platform/build/troubleshoot-trigger-timeouts.md

- **Developer Platform Login**
  - URL: https://docs.zapier.com/platform/dev-platform-login.md

- **Powered by Zapier Documentation**: Powered by Zapier is the easiest ways to embed Zapier and surface integrations within your product.
  - URL: https://docs.zapier.com/platform/embed/powered-by-zapier.md

- **Welcome**
  - URL: https://docs.zapier.com/platform/home.md

- **Active users retention**: At Zapier, churn means a user used your integration in their Zaps 29 - 56 days ago, but hasn't run a successful task in one of those Zaps in the past 28 days. This user is considered to have churned from the integration. Maybe they switched to using a competing integration or their workflow had a more periodic or seasonal cadence.
  - URL: https://docs.zapier.com/platform/manage/active-users.md

- **Invite team members to your integration**: Integrations do not have a dedicated owner, instead they are managed by a team that can be modified as needed. Add team members to your integration to collaborate, contribute, and view analytics data for your integration on the Developer Platform. Your integration team can have up to 200 team members, regardless of whether your integration is Private or Public.
  - URL: https://docs.zapier.com/platform/manage/add-team.md

- **null**: Zapier recognizes that temporary unavailability is sometimes inevitable for your API.
  - URL: https://docs.zapier.com/platform/manage/api-outage.md

- **Change authentication field keys**
  - URL: https://docs.zapier.com/platform/manage/auth-keys.md

- **Add required authentication field**
  - URL: https://docs.zapier.com/platform/manage/auth-required.md

- **Change authentication type**: If your API's authentication method changes, you’ll also need to update how Zapier authenticates user accounts in your integration.
  - URL: https://docs.zapier.com/platform/manage/auth-scheme.md

- **Change OAuth scope**: How to add or remove OAuth scopes.
  - URL: https://docs.zapier.com/platform/manage/auth-scope.md

- **Changes to your API can impact your integration**
  - URL: https://docs.zapier.com/platform/manage/change-api.md

- **Change trigger or action key**
  - URL: https://docs.zapier.com/platform/manage/change-keys.md

- **Update perform method for polling trigger**
  - URL: https://docs.zapier.com/platform/manage/change-perform.md

- **Change trigger from polling to REST Hook**
  - URL: https://docs.zapier.com/platform/manage/change-trigger.md

- **Integration CI Pipelines using Changesets and Snapshot Versions**: Use changesets with snapshot versions to set up an automated pipeline for integration version updates.
  - URL: https://docs.zapier.com/platform/manage/changeset-workflow.md

- **Clone a version**: Cloning allows you to duplicate an existing version of your integration. This is particularly useful when you want to introduce new features or fixes without altering the original integration. When a previous version of your integration has more than 5 active users, you will need to clone that version to make modifications.
  - URL: https://docs.zapier.com/platform/manage/clone.md

- **Deprecate or delete a version**: Deprecation is an optional process that allows you to set a date from which an integration version cannot be used anymore. Zapier is normally a “set it and forget it” experience for users, so use this feature carefully. Only if the version will no longer function, should it be deprecated. Please note that deprecating a version is significantly disruptive to our mutual users if a migration to a different version is not possible.
  - URL: https://docs.zapier.com/platform/manage/deprecate.md

- **Embed activation rates**: Consider all the user clicks on Zap Templates surfaced in your embeds. The embed activation rate is the percentage of those Zaps that actually activated within 24 hours of creation, meaning the Zap ran at least one successful task. It measures the efefctiveness of the Zapier embeds in your product at converting user clicks on Zap Templates to Zap activations.
  - URL: https://docs.zapier.com/platform/manage/embed-activation.md

- **Embed insights definitions**: Embed features are available for public integrations.
  - URL: https://docs.zapier.com/platform/manage/embed-insights.md

- **Improve error response handling**: Errors from your API cause pain for users at two vital points:
  - URL: https://docs.zapier.com/platform/manage/error-handling.md

- **Essential tips for integrating quality health practices**: Our shared customers rely on Zapier and your integration for business-critical workflows. Addressing feedback early and often ensures users have the best experience, both with Zapier's platform and yours. Follow these tips on how. 
  - URL: https://docs.zapier.com/platform/manage/essential-tips-iq.md

- **Export integration to Platform CLI**: The Zapier Platform CLI (Command Line Interface) is a toolset you install and run in your local development environment. It allows you to build, test, and manage your Zapier integration through JavaScript code and terminal commands.
  - URL: https://docs.zapier.com/platform/manage/export-cli.md

- **Export integration to Platform UI**: The Zapier Platform UI is the easiest way for anyone with API experience to build Zapier integrations. It is for users more comfortable with a visual form editor.
  - URL: https://docs.zapier.com/platform/manage/export-ui.md

- **Change input form field key**
  - URL: https://docs.zapier.com/platform/manage/input-key.md

- **Integration insights definitions**: Integration quality on Zapier boils down to two main pillars: **Health** and **Depth**.
  - URL: https://docs.zapier.com/platform/manage/integration-insights.md

- **Work with labeled versions**: Use labeled versions to iterate on integration changes without committing to a semantic version number.
  - URL: https://docs.zapier.com/platform/manage/labeled-versions.md

- **Migrate users to a new version**: If this isn't the first time you've promoted your app - you might have users on older versions.
  - URL: https://docs.zapier.com/platform/manage/migrate.md

- **Change output data response**
  - URL: https://docs.zapier.com/platform/manage/output.md

- **Change output field key**
  - URL: https://docs.zapier.com/platform/manage/output-key.md

- **Planning and implementing integration changes**: Before making updates to your integration, it's important to consider the potential impact on user migration and existing Zaps. Ensuring your API and Zapier integration remains backwards compatible is crucial to avoid disruption to users. However, we acknowledge certain changes are sometimes necessary and unavoidable. In such cases, consider the best practice for implementation.
  - URL: https://docs.zapier.com/platform/manage/planning-changes.md

- **Promote a version**: After your integration has entered the beta or public status, you can set a new default version for public use. This process is called promoting a version.
  - URL: https://docs.zapier.com/platform/manage/promote.md

- **Add new required input field**
  - URL: https://docs.zapier.com/platform/manage/required-input.md

- **Share your integration**: Once an integration is public, all users would have access to it when searching for an app's name in the Zap Editor, or in the [Zapier App Directory](https://zapier.com/apps).
  - URL: https://docs.zapier.com/platform/manage/sharing.md

- **Respond to user feedback and bugs**: For public integrations, Zapier's Support team logs user requests and reported problems in Zapier's issue tracker, that your team can see from the _Bug & Feature Requests_ page in the Manage section.
  - URL: https://docs.zapier.com/platform/manage/user-feedback.md

- **Version lifecycle states**: Learn about the different lifecycle states an integration version can go through, including private, promoted, available, legacy, deprecating, and deprecated versions.
  - URL: https://docs.zapier.com/platform/manage/version-lifecycle-states.md

- **Versions**: Versions in Developer Platform allow developers to create multiple iterations of their integration to experiment with and implement new features without affecting existing users. Each integration can have many versions, but only one version can have a public status at a one time.
  - URL: https://docs.zapier.com/platform/manage/versions.md

- **Manage a legacy integration**
  - URL: https://docs.zapier.com/platform/manage/versions-legacy.md

- **Zap activation rates**: Consider all of the Zaps that users try to create with your integration's triggers, actions, or searches. The Zap activation rate is the percentage of those Zaps that actually activated within 24 hours of creation, meaning the Zap ran at least one successful task.
  - URL: https://docs.zapier.com/platform/manage/zap-activation.md

- **Platform News**: Changelogs and occasional tips
  - URL: https://docs.zapier.com/platform/news.md

- **No more manual handling of 4xx errors in refreshAccessToken**: We now automatically handle 4xx error responses when refreshing OAuth2 access tokens.
  - URL: https://docs.zapier.com/platform/news/2025/4xx-errors-refreshAccessToken.md

- **Platform News in 2025**
  - URL: https://docs.zapier.com/platform/news/2025/index.md

- **Labeled Versions now available in CLI and Platform UI**: Integration version numbers can now include a label, to enable you to develop and test changes without committing to a [semantic version number](/platform/manage/versions#version-numbering) until you're ready.
  - URL: https://docs.zapier.com/platform/news/2025/labeled-versions.md

- **Incident: Unauthorized Access to Zapier NPM Packages**: Please review the enclosed list of packages and recommendations for Zapier developers.
  - URL: https://docs.zapier.com/platform/news/2025/npm-package-sec-inc.md

- **Migration UI now supports individual and organization-level migrations**: Enhanced migration UI with granular control options for individual and organization-level migrations.
  - URL: https://docs.zapier.com/platform/news/2025/organization-user-migration-in-ui.md

- **Self-serve static IP for private integrations**: Developers can now enable static IP addresses for private integrations directly in Platform UI without contacting support.
  - URL: https://docs.zapier.com/platform/news/2025/static-ip-self-serve.md

- **What's changed in v17.0.0**: ES module support, more complete typing, no more `{{curlies}}` in shorthand requests.
  - URL: https://docs.zapier.com/platform/news/2025/v17.0.0.md

- **What's changed in v17.0.1**: Fixed a regression bug on `zapier build` and the oauth2 template in `zapier init`.
  - URL: https://docs.zapier.com/platform/news/2025/v17.0.1.md

- **What's changed in v17.0.2**: Windows and ESM bugs.
  - URL: https://docs.zapier.com/platform/news/2025/v17.0.2.md

- **What's changed in v17.0.3**: Bug fixes on `zapier build`, `{{curlies}}` replacement, and more.
  - URL: https://docs.zapier.com/platform/news/2025/v17.0.3.md

- **What's changed in v17.0.4**: Fixed a bug in `zapier build`.
  - URL: https://docs.zapier.com/platform/news/2025/v17.0.4.md

- **What's changed in v17.1.0**: Improved `zapier convert` and `zapier deprecate`.
  - URL: https://docs.zapier.com/platform/news/2025/v17.1.0.md

- **What's changed in v17.2.0**: Improved large bundle handling.
  - URL: https://docs.zapier.com/platform/news/2025/v17.2.0.md

- **What's changed in v17.3.0**: Revamped `zapier build` and input field grouping.
  - URL: https://docs.zapier.com/platform/news/2025/v17.3.0.md

- **What's changed in v17.3.1**: Regression bug fixes with `zapier build`.
  - URL: https://docs.zapier.com/platform/news/2025/v17.3.1.md

- **What's changed in v17.4.0**: Regression bug fixes with `zapier build`, support for compression of large input bundles.
  - URL: https://docs.zapier.com/platform/news/2025/v17.4.0.md

- **What's changed in v17.5.0**: Global `errors`, bug fixes with `zapier build` and auth field types.
  - URL: https://docs.zapier.com/platform/news/2025/v17.5.0.md

- **What's changed in v17.6.0**: Global `console` object and account filtering for `zapier canary`.
  - URL: https://docs.zapier.com/platform/news/2025/v17.6.0.md

- **What's changed in v17.7.0**: This update lays groundwork for Search Pagination, which will allow Search steps to paginate through results so that the most relevant results can be returned. However, this is not yet supported by any Zapier products.
  - URL: https://docs.zapier.com/platform/news/2025/v17.7.0.md

- **What's changed in v17.7.1**: Improved `zapier scaffold`, `zapier init`, `zapier validate`, and `zapier invoke auth`. Also fixed issues with uncensored sensitive information and field grouping schema.
  - URL: https://docs.zapier.com/platform/news/2025/v17.7.1.md

- **What's changed in v17.7.2**: Fixed issues with typing and semver restriction.
  - URL: https://docs.zapier.com/platform/news/2025/v17.7.2.md

- **What's changed in v17.8.0**: Added flexibility for Search Pagination and cleaning up some dependencies. Zapier push now supports snapshot publishing.
  - URL: https://docs.zapier.com/platform/news/2025/v17.8.0.md

- **What's changed in v17.9.0**: Bugfix for snapshot flag, improvements for `zapier env`.
  - URL: https://docs.zapier.com/platform/news/2025/v17.9.0.md

- **What's changed in v17.9.1**: Bug fix for zapier push and dependency updates.
  - URL: https://docs.zapier.com/platform/news/2025/v17.9.1.md

- **What's changed in v18.0.0**: Node.js 22 support, new throttling middleware, and a new CLI executable name `zapier-platform`.
  - URL: https://docs.zapier.com/platform/news/2025/v18.0.0.md

- **What's changed in v18.0.1**: Bug fixes for npx resolution and TypeScript typing for line items.
  - URL: https://docs.zapier.com/platform/news/2025/v18.0.1.md

- **What's changed in v18.0.5**: A security fix on the CLI.
  - URL: https://docs.zapier.com/platform/news/2025/v18.0.5.md

- **What's changed in v18.0.6**: Package manager detection from `zapier build`
  - URL: https://docs.zapier.com/platform/news/2025/v18.0.6.md

- **Platform News in 2026**
  - URL: https://docs.zapier.com/platform/news/2026/index.md

- **What's changed in v18.0.7**: Publishing process improvements, refactoring, and `sample` field added to dynamic `outputFields`.
  - URL: https://docs.zapier.com/platform/news/2026/v18.0.7.md

- **What's changed in v18.1.0**: New `invoke --remote` flag and a fix on package manager detection.
  - URL: https://docs.zapier.com/platform/news/2026/v18.1.0.md

- **What's changed in v18.1.1**: Bug fix for missing HTTP error logs and security updates.
  - URL: https://docs.zapier.com/platform/news/2026/v18.1.1.md

- **Platform News (Single Page)**: Recent changelogs and tips on a single page
  - URL: https://docs.zapier.com/platform/news/single-page.md

- **Add or modify integration branding and details**: When creating a new integration in the Platform UI from the link `https://developer.zapier.com/app/new`, you'll be prompted to add the app name, description, homepage URL and logo.
  - URL: https://docs.zapier.com/platform/publish/add-or-modify-branding.md

- **Guide to Zapier Partner Program Benefits**: Zapier offers a variety of marketing and support benefits to partners. This cheat sheet is designed to help you understand when and how you can access each of these benefits as you unlock them.
  - URL: https://docs.zapier.com/platform/publish/benefits-guide.md

- **Best practices for showcasing your integration**: Sharing well-crafted content about your Zapier integration can help you improve user adoption, highlight key use cases, and simplify integration processes. Need some inspiration? The following examples show how some of our partners are effectively communicating their Zapier integrations across different platforms.
  - URL: https://docs.zapier.com/platform/publish/best-practices.md

- **Add integration branding in Platform CLI**: When you make a new integration in Zapier CLI, you can add the app's name, description, and homepage to the `package.json` file.
  - URL: https://docs.zapier.com/platform/publish/branding-cli.md

- **Integration branding guidelines**: When creating your integration, you'll add your app’s name, logo, description, category, and primary brand color. Consistent branding is essential for helping users recognize and discover your app on Zapier.
  - URL: https://docs.zapier.com/platform/publish/branding-guidelines.md

- **Integration build guidelines**: Before publishing your integration on Zapier, it is essential to ensure that your integration is well-prepared to provide a seamless and efficient user experience. The following guidelines are designed to assist you in refining your integration before submitting it for review. Adhering to these guidelines will help enhance the functionality and user interaction with your integration and will provide you with the best value and opportunities to harness Zapier as a method of obtaining new users and most commonly, boosting the lifetime value of your current customers.
  - URL: https://docs.zapier.com/platform/publish/integration-build-guidelines.md

- **Integration check reference**: Before you can submit your integration for publishing, it runs through a set of automated checks to ensure it's working properly and giving our users (and yours) the best possible experience.
  - URL: https://docs.zapier.com/platform/publish/integration-checks-reference.md

- **Integration publishing requirements**: We're excited you are creating an integration for the [Zapier Platform](https://zapier.com/developer-platform). We're here to help you understand our platform and its requirements so that you can successfully prepare your Zapier integration for publishing. Thousands of partners have built integrations on the Zapier Platform that enable our mutual users to set up Zaps as easily and quickly as possible.
  - URL: https://docs.zapier.com/platform/publish/integration-publishing-requirements.md

- **Integration success strategies**: With 8,000+ public integration partners on Zapier, use these 10 tried-and-true tactics from our top partners to skyrocket your growth and earn you more <a href='https://zapier.com/developer-platform/partner-program' target='_blank'>benefits from the Partner Program</a>.
  - URL: https://docs.zapier.com/platform/publish/partner-faq.md

- **Partner Program**: The [Zapier Partner Program](https://zapier.com/developer-platform/partner-program) is a program for Zapier's [8,000+ integration partners](https://zapier.com/apps). It is designed to give all public partners a clear path to success for their integrations and reward them with benefits along the way.
  - URL: https://docs.zapier.com/platform/publish/partner-program.md

- **Build your first public integration on Zapier**: This guide gives an overview of the process to publishing a public integration.
  - URL: https://docs.zapier.com/platform/publish/public-integration.md

- **Create help documentation for your users**: We encourage you to publish help documentation about using your Zapier integration on your own website. Having guides on your site gives users a seamless experience when they're already exploring your product, and allows you to tailor the documentation to your branding. While Zapier's support team will help users troubleshoot issues, having detailed help docs on your site enables users to self-serve and address common questions on their own.
  - URL: https://docs.zapier.com/platform/publish/user-help.md

- **Zap templates**: Zapier empowers apps to do together what they can't on their own. With a bit of inspiration and creativity, your users can pull dozens of apps together into unique workflows to get more done with your app in far less time.
  - URL: https://docs.zapier.com/platform/publish/zap-templates.md

- **Zapier Partner Sandbox**: Zapier Partner Sandbox is a workspace for people in your organization who are on your integration team.
  - URL: https://docs.zapier.com/platform/publish/zps.md

- **App Developer Services**: If you don't have the time or resources to dedicate towards developing your own integration, Zapier has Solution Partners who may be able to assist you. Solution Partners can build and maintain Zapier integrations for you, including private integrations, public integrations, and custom actions, making them a smart way to extend your dev team’s capacity.
  - URL: https://docs.zapier.com/platform/quickstart/app-developer-services.md

- **Build your integration on Zapier**: This guide will walk you through what steps you need to take to build an integration from start to finish. There are no fees to build an integration with Zapier.
  - URL: https://docs.zapier.com/platform/quickstart/build-integration.md

- **Platform CLI tutorial**: This tutorial walks you through the process of building, testing, and pushing an example app to Zapier using Platform CLI. We'll use a mock API for recipes in this tutorial, but for production Zapier apps, you'd want to connect to a real API.
  - URL: https://docs.zapier.com/platform/quickstart/cli-tutorial.md

- **Get help with the Zapier Platform**: Get help building your app integration through the following channels:
  - URL: https://docs.zapier.com/platform/quickstart/get-help.md

- **Zapier Glossary**
  - URL: https://docs.zapier.com/platform/quickstart/glossary.md

- **How Zapier works**: [Zapier is a tool](https://zapier.com/how-it-works) that helps you automate repetitive tasks between two or more apps, no code necessary. Our customers use Zapier to move information from one app to another automatically rather than manually. Each Zap you create starts with a trigger (something that happens in one app) and then one or more actions (something else that happens in another app).
  - URL: https://docs.zapier.com/platform/quickstart/how-zapier-works.md

- **Private vs public integrations**: When building an integration on the Zapier Platform, you must specify the intended audience.
  - URL: https://docs.zapier.com/platform/quickstart/private-vs-public-integrations.md

- **Recommended triggers and actions**: Whether you’re just starting to scope out a new Zapier integration build or have successfully launched your app in the Zapier App Directory, it’s helpful to know what features users find the most valuable and are the most widely used across Zapier’s various [app categories](https://zapier.com/apps). Ensuring your integration covers the foundational triggers, actions, and searches applicable to your app will provide more utility to your users.
  - URL: https://docs.zapier.com/platform/quickstart/recommended-triggers-and-actions.md

- **Platform UI tutorial**: This tutorial walks you through the process of building an integration on Zapier with authentication, a trigger and an action using the Platform UI.
  - URL: https://docs.zapier.com/platform/quickstart/ui-tutorial.md

- **Platform UI vs Platform CLI**: There are two different developer tools to build either private or public integrations with on the Zapier Developer Platform: Platform UI or Platform CLI.
  - URL: https://docs.zapier.com/platform/quickstart/ui-vs-cli.md

- **Zapier integration structure**: [Zapier's Developer Platform](https://developer.zapier.com/) includes everything needed to build and manage a new Zapier integration. When you access your integration project by name, you'll see the left sidebar outlines the core project structure.
  - URL: https://docs.zapier.com/platform/quickstart/zapier-integration-structure.md

- **AI actions**: Zapier's [AI Actions](https://actions.zapier.com/) is an AI alpha product designed to work with natural language-based products. It leverages the Zapier platform, with over [6000 apps](https://zapier.com/apps). You can include the capabilities of Zapier's platform in your own product.
  - URL: https://docs.zapier.com/platform/reference/ai-actions.md

- **Zapier integration structure for an AI app**: AI app integrations built on Zapier allow users to automate tasks using AI capabilities. Here are some common pain points and recommendations when building AI apps on Zapier.
  - URL: https://docs.zapier.com/platform/reference/ai-app.md

- **CLI command reference**
  - URL: https://docs.zapier.com/platform/reference/cli.md

- **Cloning a version**: Cloning allows you to duplicate an existing version of your integration. This is particularly useful when you want to introduce new features or fixes without altering the original integration. When a previous version of your integration has more than 5 active users, you will need to clone that version to make modifications.
  - URL: https://docs.zapier.com/platform/reference/cloning-a-version-tutorial.md

- **Zapier integration structure for a CRM app**: CRM (customer relationship management) apps are detailed databases that link contacts with companies, companies with deals, and more.
  - URL: https://docs.zapier.com/platform/reference/crm-app.md

- **Custom actions and API requests actions**: [Custom Actions](https://help.zapier.com/hc/en-us/articles/16276574838925-App-Extensions-in-Zapier) and [API Requests](https://help.zapier.com/hc/en-us/articles/12899607716493-Set-up-an-API-request-action#prerequisites-0-0) are features that have been developed internally at Zapier, designed to help our mutual customers achieve the most value out of your app integration.
  - URL: https://docs.zapier.com/platform/reference/custom-actions-api-requests.md

- **Using Dictionary Fields**: Dictionary fields allows your users to directly send an object with their provided value sets to your API.
  - URL: https://docs.zapier.com/platform/reference/dictionary-fields-tutorial.md

- **Creating dynamic dropdown fields**: Dynamic dropdown fields are useful when users need to select data from an existing list of similar data in their account on your app.
  - URL: https://docs.zapier.com/platform/reference/dynamic-dropdown-tutorial.md

- **Implementing Error Handling**: Error handling enables you dictate how your integration should function when certain errors are returned from your API.
  - URL: https://docs.zapier.com/platform/reference/error-handling-tutorial.md

- **Zapier integration structure for a forms app**: Form and survey app integrations built on Zapier allow users to connect mobile data collection forms to send the responses into other apps as new contacts, document templates, messages, and more.
  - URL: https://docs.zapier.com/platform/reference/forms-app.md

- **Implementing OAuth v2 authentication**: With OAuth v2 authentication, users authenticate to the Zapier integration via the app’s own site, helping them to easily connect accounts without needing to share account credentials or look up API keys.
  - URL: https://docs.zapier.com/platform/reference/implementing-oauth-tutorial.md

- **Scripting in converted legacy Web Builder integrations**: This guide provides instructions on editing and maintaining existing scripting methods for legacy web builder integrations that have been converted to either the Platform UI or Platform CLI.
  - URL: https://docs.zapier.com/platform/reference/legacy-scripting.md

- **Managing integration team members**: Integrations do not have a dedicated owner, instead they are managed by a team that can be modified as needed. Members can be added to a Zapier integration and can also be removed from the integration when needed.
  - URL: https://docs.zapier.com/platform/reference/managing-team-tutorial.md

- **Utilizing the Monitoring Tool**: The Monitoring Tool gives you access to logs for requests made to your API by your Zapier integration
  - URL: https://docs.zapier.com/platform/reference/monitoring-tool-tutorial.md

- **Zapier integration structure for a project management app**: While you can't automate project work, you can automatically add tasks, create new projects, and keep track of progress via an app integration on Zapier.
  - URL: https://docs.zapier.com/platform/reference/project-app.md

- **Promoting a version**: Promoting a version makes an integration version the new default version for a public integration
  - URL: https://docs.zapier.com/platform/reference/promoting-a-version-tutorial.md

- **Utilizing Request Template**: The Request Template is a request editor that lets users set static values that apply to all requests made by this integration.
  - URL: https://docs.zapier.com/platform/reference/request-template-tutorial.md

- **Implementing REST Hook triggers**: REST Hook triggers runs in near realtime as it involves your app pushing data to Zapier as soon as new data comes into your app.
  - URL: https://docs.zapier.com/platform/reference/rest-hook-trigger-tutorial.md

- **Schema reference**
  - URL: https://docs.zapier.com/platform/reference/schema.md

- **Transfer**: [Transfer](https://help.zapier.com/hc/en-us/articles/8496274335885) is a Zapier functionality that enables users to perform bulk operations using their historical data.
  - URL: https://docs.zapier.com/platform/reference/transfer.md

- **Using Environment Variables**: Environment variables are useful when you have data like an OAuth client ID and secret that you don’t want to commit to source control. Environment variables can also be used as a way to toggle between a staging and production environment during app development and this would be recommended instead of the use of an independent integration for staging purposes.
  - URL: https://docs.zapier.com/platform/reference/using-environment-variables-tutorial.md

- **Embedding the Zapier Workflow Element**: The Zapier Workflow Element is a prebuilt UI component that enables you to suface your Zapier integration and user workflows directly in your app
  - URL: https://docs.zapier.com/platform/reference/zapier-workflow-element-tutorial.md

- **Zap Guesser**: Quickly generate intelligent Zap suggestions from natural language prompts.
  - URL: https://docs.zapier.com/powered-by-zapier/ai-workflows/zap-guesser.md

- **Create Account**: Create a new user and obtain an access token. See our Quick Account Creation guide to get started.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/accounts/create-account.md

- **User Profile**: This endpoint returns the authenticated user information
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/accounts/user-profile.md

- **Create an Action Run**: Runs an action (step) in the third party API, using the provided authentication and inputs.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/actions/create-an-action-run.md

- **Get Actions**: Fetch the available actions for the provided App. It's typical to filter by type so that only actions that make sense for a particular step are shown. Action IDs may not be reused, see our documentation for how to hardcode a particular action.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/actions/get-actions.md

- **Get Choices**: Get the possible values for a `SELECT` Input Field.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/actions/get-choices.md

- **Get Input Fields**: Get the Input Fields for a particular Action, using the provided authentication and inputs. See the fields and fieldsets guide for more information.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/actions/get-input-fields.md

- **Get Output Fields**: Get the Output Fields for a particular Action, using the provided authentication and inputs.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/actions/get-output-fields.md

- **Retrieve Action Run**: Retrieves an Action Run.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/actions/retrieve-action-run.md

- **Step Test**: Tests the action (step) in the third party api, using the provided authentication and inputs.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/actions/step-test.md

- **Link**: [Get Apps [v1]]( This endpoint returns a list of apps sorted popularity. See the List Apps guide to get started.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/apps/get-apps-[v1].md):

- **Link**: [Get Apps [v2]]( This endpoint returns a list of apps sorted by popularity.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/apps/get-apps-[v2].md):

- **Create Authentication**: Creates a new Authentication for the provided App. See our Adding an Authentication guide to get started.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/authentications/create-authentication.md

- **Get Authentications**: Fetch the available Authentications for the provided App. This will only return Authentications that are owned by the user and not those that are shared with them, since it's not possible to create Zaps with Authentications you don't own.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/authentications/get-authentications.md

- **Get Categories**: List of Zap categories
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/categories/get-categories.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/action.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/app.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/authentication.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/choice.md

- **Common Types**: Description Goes here
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/common-types.md

- **Errors**: Errors in the API follow the <a href="https://jsonapi.org/format/#error-objects" target="_blank">recommendation</a> from the JSON API spec.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/errors.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/fieldset.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/infoField.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/inputField.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/outputField.md

- **Pagination**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/pagination.md

- **Requests**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/requests.md

- **Responses**: Responses for the API follow the <a href="https://jsonapi.org/format/#fetching-resources-responses-200" target="_blank">JSON API spec</a> for fetching resources.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/responses.md

- **null**
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/common-types/zap.md

- **Get Zap Runs**: This endpoint returns runs for the specified Zaps and provides basic yet essential details about their execution. As the initial version, it serves foundational information, with plans for continuous enhancement to expand its capabilities and improve data output over time.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/experimental/get-zap-runs.md

- **Create Promotion Enrollment**: Enrolls an account into an existing promotion.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/promotions/create-enrollment.md

- **Delete Promotion Enrollment**: Unenroll an account from a promotion.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/promotions/delete-enrollment.md

- **Get Promotion Enrollment**: Retrieve promotion enrollment details by enrollment ID.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/promotions/get-enrollment.md

- **Rate Limiting**: Rate limits when accessing the Workflow API   
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/rate-limiting.md

- **Get Zap Templates**: List popular Zap Templates using your app. See our List Zap Templates guide to get started.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/zap-templates/get-zap-templates.md

- **Create a Zap**: This URL creates a Zap based on the given steps and title.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/zaps/create-a-zap.md

- **Link**: [Get Zaps [v1]]( This endpoint returns a list of Zaps for the authenticated Zapier user.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/zaps/get-zaps-[v1].md):

- **Link**: [Get Zaps [v2]]( This endpoint returns a list of Zaps for the authenticated Zapier user.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/zaps/get-zaps-[v2].md):

- **Link**: [Guess a Zap [Beta]]( This endpoint returns a suggested Zap and pre-filled URL to Zapier from a given prompt.
  - URL: https://docs.zapier.com/powered-by-zapier/api-reference/zaps/guess-a-zap.md):

- **Getting Started**: Authenticate with The Zapier Workflow API
  - URL: https://docs.zapier.com/powered-by-zapier/authentication/getting-started.md

- **App Access Token**: How to authenticate with an App Access Token
  - URL: https://docs.zapier.com/powered-by-zapier/authentication/methods/app-access-token.md

- **Client ID**: How to authenticate with your Client ID
  - URL: https://docs.zapier.com/powered-by-zapier/authentication/methods/client-id.md

- **User Access Token**: How to authenticate with a User Access Token
  - URL: https://docs.zapier.com/powered-by-zapier/authentication/methods/user-access-token.md

- **Getting Started**: Embed Zapier MCP into your application to enable your users to connect to thousands of apps and execute actions directly from your agent interface.
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier-mcp/getting-started.md

- **Connecting Your Agent**: Learn how to connect your agent to Zapier MCP servers.
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier-mcp/guides/connecting-your-agent.md

- **Getting Embed Code**: Generate embed code snippets for integrating Zapier MCP into your application.
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier-mcp/guides/getting-embed-code.md

- **Element Security**: Keeping our elements secure and usable is critical at Zapier
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier/elements-security.md

- **Embed Insights**: Insights are available to review the performance of your embed, and track usage growth.
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier/embed-insights.md

- **Getting Started**: With an embedded Zap editor in your product, your users can create and edit their Zaps without leaving your app.
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier/getting-started.md

- **Pre-filled Zaps**: Prefills allow you to define the input fields on behalf of the user, simplying the experience of setting up their Zap.
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier/pre-filled-zaps.md

- **Workflow Element**: The Workflow Element is a prebuilt UI component that offers the quickest—and easiest—way to surface your Zapier integration directly within your own product.
  - URL: https://docs.zapier.com/powered-by-zapier/embedding-zapier/workflow-element.md

- **Introduction**: Add automation to your product—without building it from scratch.
  - URL: https://docs.zapier.com/powered-by-zapier/introduction.md

- **Adding App Authentications**: Reduce friction when adding an authentication to your own app.
  - URL: https://docs.zapier.com/powered-by-zapier/managing-app-authentication/adding-app-authentications.md

- **Get Authentications**: Retrieve Authentications for a specific App, scoped to those owned by the user.
  - URL: https://docs.zapier.com/powered-by-zapier/managing-app-authentication/get-authentications.md

- **Getting Started**: Learn more about App Authentications
  - URL: https://docs.zapier.com/powered-by-zapier/managing-app-authentication/getting-started.md

- **Creating Action Runs**
  - URL: https://docs.zapier.com/powered-by-zapier/running-actions/create-action-run.md

- **Getting Started**: How To Run An Action
  - URL: https://docs.zapier.com/powered-by-zapier/running-actions/getting-started.md

- **Retrieving Action Run Results**
  - URL: https://docs.zapier.com/powered-by-zapier/running-actions/retrieve-action-run.md

- **Getting Started**: Offer Zapier-powered automation without requiring your users to manage their own Zapier accounts or billing.
  - URL: https://docs.zapier.com/powered-by-zapier/sponsor-user-automation/getting-started.md

- **User Enrollment**: Seamlessly enroll users in promotions to unlock exclusive benefits with a single API call.
  - URL: https://docs.zapier.com/powered-by-zapier/sponsor-user-automation/user-enrollment.md

- **Versioning**
  - URL: https://docs.zapier.com/powered-by-zapier/versioning.md

- **Fields and Fieldsets**
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/fields-and-fieldsets.md

- **Filter Actions**: Learn how to configure Filter by Zapier actions to control workflow execution based on conditions.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/filter-actions.md

- **Getting Started**: Our most powerful tool for building native workflows in your product
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/getting-started.md

- **Hardcoding an Action**: To help focus the user experience, it can be helpful to hardcode a certain Action to guide users in selecting the most appropriate action for their use-case.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/hardcoding-an-action.md

- **How to Build a Workflow**: This guide walks through the entire process of building an automated workflow for your users to use -- from picking apps, adding authentication, filling inputs and publishing.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/how-to-build-a-workflow.md

- **Known Limitations**: Creating workflows using the Zapier Workflow API is a recent addition, and there are some known limitations.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/known-limitations.md

- **Quick Account Creation**: Quick Account Creation is a seamless, accelerated sign-up feature allowing first time Zapier users to skip the standard sign-up procedure and onboarding survey. Enabling Quick Account Creation as part of your embed tool code helps provide a more frictionless experience for end users.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/quick-account-creation.md

- **Retrieving a list of Zaps**: Listing a users zaps reveals existing workflows created by users.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/retrieving-a-list-of-zaps.md

- **Retrieving Apps**: Listing apps available on Zapier is a simple way to show users all of what's possible on Zapier
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/retrieving-apps.md

- **Selecting an Action**: An Action is an operation that can be performed against a third-party API; such as a `READ` or a `WRITE`.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/selecting-an-action.md

- **Selecting an Authentication**: Support users in selecting 3rd party authentications, either through an existing authentication or by adding new.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/selecting-an-authentication.md

- **Testing a Workflow**: Step testing allows for the validation of a configured step, by execiting the defined action.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-creation/testing-a-workflow.md

- **Getting Started**: Embed pre-built automations directly into your product.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-templates/getting-started.md

- **Retrieving Zap Templates**: Zap templates are pre-made Zaps that help users discover popular use cases for automating their work. Each template features a specific use case and the apps needed for it to work.
  - URL: https://docs.zapier.com/powered-by-zapier/zap-templates/retrieving-zap-templates.md

## Additional Resources (Optional)

### Optional

- **Community**
  - URL: https://community.zapier.com/

- **Blog**
  - URL: https://zapier.com/blog/

- **Contact Us**
  - URL: https://developer.zapier.com/contact

## How to Use This Skill

Reference these resources when working with Zapier.