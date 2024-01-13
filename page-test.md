# The Glossary


This list highlights select Bubble-specific terms you might encounter in the user manual and core reference. It focuses on terms with unique meanings within Bubble.

Many items on the list provide links to articles and core reference materials, offering deeper insights into the concepts and practical applications of the associated keyword.

Use the search feature in your browser to quickly find the term or phrase that you are looking for. Search is usually activated with *CTRL+F* or *⌘ + F*.

Action


- An action is a part of a workflow
- It is a step that a Bubble workflow takes, i.e. the different kinds of things that workflows can do
- Examples include sending an email, logging the user in, showing an element, hiding an element, etc.

Learn more](https://manual.bubble.io/the-glossary#learn-more)[

Article series: [Workflows](https://manual.bubble.io/help-guides/logic/workflows) Article: [Actions](https://manual.bubble.io/help-guides/logic/workflows/actions)​

Core reference: [List of all actions](https://manual.bubble.io/core-resources/actions)​

Alert


- The alert is an element type in Bubble that you can add to the page
- It can be set to be displayed at any given place on the page, or stick to the top of the page.
- It's not visible to the user until you trigger it using the *Show message in alert box* action.
- It's disappears a short (customizable) time after it is displayed.
- It's useful for showing a quick warning, error, or confirmation message.

API


- API is an umbrella term for allowing two apps or systems to exchange data
- Bubble can accept inbound API requests and send outbound requests:
	- **Outbound**: made via the [API Connector plugin](https://manual.bubble.io/the-glossary#api-connector-plugin)​
	- **Inbound**: made via the [Bubble API](https://manual.bubble.io/the-glossary#bubble-api)​

Learn more:


- Article series: [API](https://manual.bubble.io/help-guides/integrations/api)​

API Connector (plugin)


- The API Connector is a Bubble-built plugin that lets you set up outbound API connections with external services
- Can set up the API calls to be used as data sources or workflow actions​
- Can be installed via the plugins library (Plugins > Add Plugins)

Learn more](https://manual.bubble.io/the-glossary#learn-more-1)[

Article series: [The API Connector](https://manual.bubble.io/help-guides/integrations/api/the-api-connector) Article: [API Connector security](https://manual.bubble.io/help-guides/infrastructure/security/api-security/api-connector-security)​

Core reference: [API Connector properties](https://manual.bubble.io/core-resources/bubble-made-plugins/api-connector)​

API workflows


- A type of backend workflow which can be triggered via another workflow anywhere in the app or via an API call
- These are defined in the "Backend workflows" page, which shows up in the page selector dropdown in the topnav, once the feature is [turned on in Settings > API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api/the-workflow-api/api-workflows#activating-and-accessing-the-backend-workflow-editor)​
- These can be scheduled to run at a later time
- If the app's Workflow API is turned on, then an API workflow can also be initiated by an external API call to the app

Learn more](https://manual.bubble.io/the-glossary#learn-more-2)[

Article series: [The Bubble API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api) Article series: [The Workflow API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api/the-workflow-api)​

Core reference: [API workflow properties](https://manual.bubble.io/core-resources/api/the-bubble-api/the-workflow-api)​

App connector (plugin)


- A feature that lets you connect two Bubble apps so that they interact with one another more seamlessly (as opposed to connecting the two strictly via APIs as if one was a third party)
- Can be installed via the [plugins](https://manual.bubble.io/the-glossary#plugin) library (Plugins > Add Plugins)
- To learn more, see [section in the Reference](https://manual.bubble.io/core-resources/bubble-made-plugins/bubble-app-connector)​

Learn more](https://manual.bubble.io/the-glossary#learn-more-3)[

Article: [The app connector plugin](https://manual.bubble.io/help-guides/integrations/bubble-app-connector)​

Core reference: [Bubble app connector properties](https://manual.bubble.io/core-resources/bubble-made-plugins/bubble-app-connector)​

Atom


- Each block of a dynamic expression is known as an atom
- Atoms can be:
	- A [data source](https://manual.bubble.io/the-glossary#data-source)​
	- An [operator](https://manual.bubble.io/the-glossary#operator)​
	- A [comparison](https://manual.bubble.io/the-glossary#comparison)​

Backend workflow


- *Backend workflows* is the umbrella term for any type of workflow you can create in the backend editor.
- This is a category of workflow that runs independently of any page of your app - they run in the "backend"

Learn more](https://manual.bubble.io/the-glossary#learn-more-4)[


- Article: [The back-end versus the front-end](https://manual.bubble.io/help-guides/logic/the-frontend-and-backend)​
- Article section: [Bubble API terminology: Backend workflows](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api/bubble-api-terminology#whats-the-difference-between-backend-workflows-and-api-workflows)​
- Article series: [The Bubble API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api)​

Branch


- A branch is an independent iteration of your application that can be developed in isolation.
- You can see the creation of a branch as splitting your app into two copies, kind of like two cells dividing. The cells are genetically identical clones at first, but can keep evolving independently of each other.
- This is useful if you have different developers/teams that are working on specific features in your app: they can work completely independently without disturbing each other's work
- Branches are a part of the [version control](https://manual.bubble.io/the-glossary#version-control) feature

Learn more](https://manual.bubble.io/the-glossary#learn-more-5)[

Article series: [Version control](https://manual.bubble.io/help-guides/maintaining-an-application/version-control)​

Bubble API


- The Bubble API is the umbrella term for Bubble's API features
	- The [Workflow API](https://manual.bubble.io/the-glossary#workflow-api)​
		- Allows external apps and systems to execute workflows in your app
	- The [Data API](https://manual.bubble.io/the-glossary#data-api)​
		- Gives external apps and systems secure access to your database
- The Bubble API offers security in two different ways
	- **Authentication**
		- The process of determining *who* is trying to access the resource
	- **Privacy rules**
		- Conditions applied to data in your database that determines whether the authenticated client has access to search for, read, change or delete data of a specific type
- The Bubble API is for *inbound* API calls (calls made *to* your app from the outside) as opposed to outbound calls that are made with the [API connector plugin](https://manual.bubble.io/the-glossary#app-connector-plugin))

Using the Bubble API is among Bubble's most advanced features, but it also offers vast possibilities for integration with other online platforms.

Cell


- Each individual row or column in a repeating group or table element is called a *cell*.
- Each cell's data source automatically represents the cell's index in the list of loaded data (for example, if you load a list of *users*, each cell will have one user as its data source)
- Each cell has an index number, starting with 1 and increasing sequentially

Learn more](https://manual.bubble.io/the-glossary#learn-more-6)[

Article: [Repeating groups](https://manual.bubble.io/help-guides/design/elements/containers/repeating-groups) Article: [Finding data](https://manual.bubble.io/help-guides/data/the-database/finding-data)​

Core reference: [Repeating group properties](https://manual.bubble.io/core-resources/elements/containers#repeating-group)​

Collaborator / Collaboration


- Any Bubble user that you invite to edit your app is called a collaborator
- You can control the access level of each collaborator in the *Collaboration* setting

Learn more](https://manual.bubble.io/the-glossary#learn-more-7)[

Article: [Collaboration](https://manual.bubble.io/help-guides/maintaining-an-application/collaboration)​

Comparison


- A comparison is a part of a [dynamic expression](https://manual.bubble.io/the-glossary#dynamic-expression)​
	- Each part of a dynamic expression is known as an [atom](https://manual.bubble.io/the-glossary#atom)​
- It's used to compare two values, such as:
	- Checking whether to users have the same name
	- Checking whether the number 4 is bigger than the number 5
	- Checking whether the creator of a [database thing](https://manual.bubble.io/the-glossary#thing-database) is the current user
- A comparison will return either a *yes* or *no*
	- If you come from a traditional programming background, this would be the same as *true* or *false*

Learn more](https://manual.bubble.io/the-glossary#learn-more-8)[

Article: [Dynamic expressions](https://manual.bubble.io/help-guides/logic/dynamic-expressions)​

Current user


- The current user is a [data source](https://manual.bubble.io/the-glossary#data-source) which returns the [database thing](https://manual.bubble.io/the-glossary#thing-database) of the currently logged-in [user](https://manual.bubble.io/the-glossary#user)​
	- If no user is logged in, it will return a temporary user profile that you can still save data to
- Using the current user data source, you can return data such as *Current user's email* in a [dynamic expression](https://manual.bubble.io/the-glossary#dynamic-expression)​

Learn more](https://manual.bubble.io/the-glossary#learn-more-9)[


- Article: [User accounts](https://manual.bubble.io/help-guides/data/user-accounts)​

Constraint / search constraint


- A search constraint narrows down the results of a database search by specifying certain conditions that the data must meet
- For example, you can search for all users called "Jane Doe" by setting up a constraint that specifies that the field called *name* should contain the text *Jane Doe*.
- You can add as many constraints as you want to a search
- Adding more constraints can lead to a faster search, since it helps Bubble rule out things quicker

Learn more](https://manual.bubble.io/the-glossary#learn-more-10)[

Article: [Finding data](https://manual.bubble.io/help-guides/data/the-database/finding-data)​

Core reference: [Search](https://manual.bubble.io/core-resources/data/search)​

Custom event


- A custom event is a workflow that can be triggered by other workflows using the *Trigger a custom event* or *Schedule a custom event* actions.
- You can customize the parameters that are passed to the custom event, and set them as optional or required as needed

Learn more](https://manual.bubble.io/the-glossary#learn-more-11)[

Article: [Custom events](https://manual.bubble.io/help-guides/logic/workflows/events/frontend-events/custom-events)​

Core reference: [Custom event properties](https://manual.bubble.io/core-resources/events/custom-events)​

Custom state


- A custom state is a way to store temporary variables on an element that can be accessed from anywhere on the same page and during the same session
- Custom states are reset when the page is refreshed, meaning they don't store data permanently
- They can hold any kind of data like text, numbers, dates or custom data types and can be read, changed and reset as needed using [actions](https://manual.bubble.io/the-glossary#action)​
- Custom states can hold a default value

Learn more](https://manual.bubble.io/the-glossary#learn-more-12)[

Article: [Custom states](https://manual.bubble.io/help-guides/data/temporary-data/custom-states)​

Data API


- The Data API is the part of the Bubble API that lets you invite other apps and systems to read and make changes in your app's database securely
- Allows querying of data, as well as creating, updating and deleting
- You can secure the Data API using authentication and privacy rules
- Must be enabled in *Settings - API*

Learn more](https://manual.bubble.io/the-glossary#learn-more-13)[

Article series: [The Bubble API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api) (the Data API is a part of the Bubble API) Article series: [The Data API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api/the-data-api)​

Core reference: [The Data API](https://manual.bubble.io/core-resources/api/the-bubble-api/the-data-api) (includes a [list of all request types](https://manual.bubble.io/core-resources/api/the-bubble-api/the-data-api/data-api-requests))

Data source


- A data source is any source from which Bubble can pull data, such as:
	- A database search
	- An outbound API request
	- The current user, current date/time and current geographical location

Learn more](https://manual.bubble.io/the-glossary#learn-more-14)[

Article series: [Data](https://manual.bubble.io/help-guides/data)​

Core reference: [List of data sources](https://manual.bubble.io/core-resources/data/data-sources)​

Database


- The database is where you store dynamic data in your app
	- It can be created by you, or added by your app's users
- Every app has its own two databases;
	- Development
	- Live
- They two are completely independent, so that you can use one for testing and one for live users
- You can create [custom data types](https://manual.bubble.io/the-glossary#data-type) in your app to suit your own needs. For example, you might want to create data types like *projects, blog posts, tasks* or *blog posts*.
	- To each of these data types, you can add *[fields](https://manual.bubble.io/the-glossary#field-field-type)* that contain data
- Bubble is designed to allow you to set up and configure your database with no prior knowledge, but the underlying technology is PostgreSQL

Learn more](https://manual.bubble.io/the-glossary#learn-more-15)[

Article series: [The database](https://manual.bubble.io/help-guides/data/the-database)​

Deploying


- Deploying your Bubble app means pushing the changes you've made in the development environment to the live environment.
- This allows users to see and interact with the latest version of your app.
- Think of it as publishing or updating your app for the public.

Learn more](https://manual.bubble.io/the-glossary#learn-more-16)[

Article: [Deploying your app](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/deploying-your-app) Article series: [Version control](https://manual.bubble.io/help-guides/maintaining-an-application/version-control) (working with different app branches in isolation and deploying those changes)

Do a search for


- *Do a search for* is a [data source](https://manual.bubble.io/the-glossary#data-source) in a [dynamic expression](https://manual.bubble.io/the-glossary#dynamic-expression), that performs a database search
- You can add [constraints](https://manual.bubble.io/the-glossary#constraint-search-constraint) to each search to narrow down the results

Learn more](https://manual.bubble.io/the-glossary#learn-more-17)[

Article: [Finding data](https://manual.bubble.io/help-guides/data/the-database/finding-data)​

Core reference: [Search](https://manual.bubble.io/core-resources/data/search)​

Data type


- A data type is any *type* of record that you set up your database, such as users, products, blog posts, tasks or whatever your app needs
- The *user* data type is built-in and cannot be deleted, but you can add as many fields as you need to it
- Data types apart from the built-in *user* type are known as *custom data types*

Learn more](https://manual.bubble.io/the-glossary#learn-more-18)[

Article series: [Data](https://manual.bubble.io/help-guides/data)​

Debugger


- Bubble comes with a set of built-in debugging tools
- They let you debug workflows and elements in run-time (while you preview your app)
- The debugger appears automatically at the bottom of the screen when you preview your app

Learn more](https://manual.bubble.io/the-glossary#learn-more-19)[


- Article: [Debugging your app](https://manual.bubble.io/help-guides/maintaining-an-application/testing-and-debugging)​
- Article: [Previewing your app](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/previewing-your-app)​

Dynamic expression


- Dynamic expressions are like "live" formulas that update in real-time based on user input, database updates and other changes in your app.
- Dynamic expressions consist of three different building blocks called *atoms*:
	- ​[Data source](https://manual.bubble.io/the-glossary#data-source): any source of data
	- Operators: functions or actions that can be performed on the data source, such as counting, sorting and calculating
	- Comparisons: compare two compatible values, such as two numbers, data types or strings of text and get a yes/no result

Learn more](https://manual.bubble.io/the-glossary#learn-more-20)[

Article: [Dynamic expressions](https://manual.bubble.io/help-guides/logic/dynamic-expressions)​

Core reference: [list of data sources](https://manual.bubble.io/core-resources/data/data-sources) Core reference: [list of operators and comparisons](https://manual.bubble.io/core-resources/data/operations-and-comparisons)​

Edit mode


- When you are editing your app in the Bubble editor, as opposed to *Run mode.*

Learn more](https://manual.bubble.io/the-glossary#learn-more-21)[


- Article: [The Bubble editor](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor)​

Editor, the / Bubble editor


- The tool you use to edit your Bubble app
- Consists of the tabs (click for relevant articles)
	- ​[Design](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/design-tab)​
	- ​[Workflow](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/workflow-tab)​
	- ​[Data](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/data-tab)​
	- ​[Styles](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/styles-tab)​
	- ​[Plugins](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/plugins-tab)​
	- ​[Settings](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/settings-tab)​
	- ​[Logs](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/logs-tab)​

Learn more](https://manual.bubble.io/the-glossary#learn-more-22)[

Article: [The Bubble editor](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor)​

Element


- Elements are the objects you place on the page when you design your app, such as text, buttons, images, icons and calendars
- Everything visible on a Bubble page is an element
- They are generally self-contained pieces of content that a user can see and potentially interact with

Learn more](https://manual.bubble.io/the-glossary#learn-more-23)[

Article series: [Design](https://manual.bubble.io/help-guides/design) Article series: [Elements](https://manual.bubble.io/help-guides/design/elements)​

Environments (Development/Live)


- All deployed Bubble application consist of two different environments:
	- The **Development environment** allows you to develop and preview your app exactly as it will look when deployed. When testing changes in a branch in the Development environment, the Development database will get populated with test data, which you can view by going to the Data tab and toggling to the Development database.
	- The **Live environment** contains your live app, which is read-only. When users interact with your live app, the Live database will get populated with live data, which you can view by going to the Data tab and toggling to the Live database by clicking Switch to Live database.
- Environments are part of the [version control](https://manual.bubble.io/the-glossary#version-control) feature

Learn more](https://manual.bubble.io/the-glossary#learn-more-24)[

Article: [Previewing your app](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/previewing-your-app) Article series: [Version control](https://manual.bubble.io/help-guides/maintaining-an-application/version-control)​

Event


- Events are the triggers that start a workflow
- Examples include:
	- An element being clicked
	- Certain data changing
	- A input form's value changing
	- A condition is true

Article series: [Workflows](https://manual.bubble.io/help-guides/logic/workflows) Article: [Events](https://manual.bubble.io/help-guides/logic/workflows/events)​

Core reference: [list of all events](https://manual.bubble.io/core-resources/events)​

Field / field type


- A field is the actual place in a [data type](https://manual.bubble.io/the-glossary#data-type) where the data is stored, and a data type can have many fields
- For example, on the built-in *user* data type, you might have the fields:
	- First name (text)
	- Last name (text)
	- Address (address)
- Some fields are built in:
	- Created date
	- Modified date
	- Unique ID
	- Slug
	- Email (only on the *user* data type)
- Fields can also contain a *list* of a specific type, such as a list of numbers, texts or custom data types

Learn more](https://manual.bubble.io/the-glossary#learn-more-25)[

Article series: [Data](https://manual.bubble.io/help-guides/data) Article: [Data types and fields](https://manual.bubble.io/help-guides/data/the-database/data-types-and-fields)​

Group


- A group is a container element, used to contain other elements
- You can load data into a group, and refer to that data on the elements within it
	- For example, you can load a user into a group, and then show the users email using a text element and the [dynamic expression](https://manual.bubble.io/the-glossary#dynamic-expression) *Parent group's user's email*.
- Groups are also a way to control [responsive behavior](https://manual.bubble.io/the-glossary#responsive-design) in your app
- You can show and hide groups to navigate within the same page
	- You can collapse their width and height when hidden to set up single-page-application

Learn more](https://manual.bubble.io/the-glossary#learn-more-26)[

Article: [The Group element](https://manual.bubble.io/help-guides/design/elements/containers/groups)​

Core reference: [List of container properties](https://manual.bubble.io/core-resources/elements/containers)​

Login


- In this context, we mean logging into your *app* and not to your Bubble account
- Bubble features a built-in, secure login system that lets users [create an account](https://manual.bubble.io/the-glossary#user) and log in using their preferred credentials
- Using [plugins](https://manual.bubble.io/the-glossary#plugin), you can also allow users to log in using a third-party service like Google or Facebook
- Before users can log in, they must [sign up](https://manual.bubble.io/the-glossary#signing-up)​

Learn more](https://manual.bubble.io/the-glossary#learn-more-27)[


- Article: [User accounts](https://manual.bubble.io/help-guides/data/user-accounts)​

Logs / Server logs


- Every server-side action performed in a Bubble app is logged and can be viewed in the *Logs* tab in the Bubble editor
- You can use this for debugging your app by auditing the operations that have taken place at a specific time or by a specific user

Learn more](https://manual.bubble.io/the-glossary#learn-more-28)[

Article: [Server logs](https://manual.bubble.io/help-guides/maintaining-an-application/testing-and-debugging/using-server-logs)​

Operator


- An operator is part of a [dynamic expression](https://manual.bubble.io/the-glossary#dynamic-expression)​
- Operators are used to manipulate or aggregate data from a [data source](https://manual.bubble.io/the-glossary#data-source). For example:
	- Turning a string of text into UPPERCASE
	- Counting the number of characters in a string of text
	- Calculating the the number of results of a search
- Operators can be chained together
- Bubble will show relevant operators as you build your expression; or example, the *:number of characters* operator will be visible when you are working with text, but not when you are working numbers

Learn more](https://manual.bubble.io/the-glossary#learn-more-29)[

Article: [Dynamic expressions](https://manual.bubble.io/help-guides/logic/dynamic-expressions)​

Core reference: [list of operators](https://manual.bubble.io/core-resources/data/operations-and-comparisons)​

Option set


- An option set is a static collection of options that can contain multiple fields
- It behaves in much the same way as data types, but are not dynamic
	- This means they cannot be changed without re-deploying your app
	- It also means they cannot be updated by your users: only by a Bubble developer with access to the [Bubble editor](https://manual.bubble.io/the-glossary#editor-the-bubble-editor)​
- They become part of your app's source code
	- This means they load faster than the database, and remains cached on the user's device
	- It also means they should not contain any sensitive data, since they are downloaded in plaintext to every device that accesses ay page in your app
- Option sets are great for storing data that doesn't change frequently, such as a list of:
	- Colors
	- Countries/states
	- Menu options
	- Dropdown options

Learn more](https://manual.bubble.io/the-glossary#learn-more-30)[

Article: [Option sets](https://manual.bubble.io/help-guides/data/static-data/option-sets)​

Plugin


- Plugins are extensions that you can install to add features, elements or integrates third-party services.
- The plugin store features thousands of plugins.
	- Some are made by Bubble, while most are made by third parties
	- Some are free, while others require a one-time payment or subscription to use
- Plugins are installed and paid per app, not per Bubble account
- Agencies using the agency plan can install and use all plugins for free while the app is in development.

Learn more](https://manual.bubble.io/the-glossary#learn-more-31)[

Article: [Plugins](https://manual.bubble.io/help-guides/integrations/using-plugins)​

Privacy / privacy rules


- Privacy refers to the protection of user data and information, ensuring it's accessed and shared only by the right user(s)
- Privacy and security are closely intertwined, but are not the same thing: privacy is a policy, while security is what maintains that policy
- Bubble uses privacy rules to protect data in the database from ever leaving the server if the user is not authorized to access it
- Privacy rules also protect data accessed through the Bubble API
- Privacy rules are applied to each data type as a condition (i.e. "If this user is logged in, they can access the data)

Learn more](https://manual.bubble.io/the-glossary#learn-more-32)[

Article: [Protecting data with privacy rules](https://manual.bubble.io/help-guides/data/the-database/protecting-data-with-privacy-rules) Article series: [Bubble security](https://manual.bubble.io/help-guides/infrastructure/security)​

Core reference: [Privacy rules settings](https://manual.bubble.io/core-resources/data/privacy)​

Property editor


- The property editor is the part of the Design tab that appears when you double-click on an element or click it in the element tree
- It's where you control the properties of that element
	- Different element types have different properties
- It can be made to always be visible by toggling *View > Lock Property Editor*
- This is also where you control an element's responsive properties

Learn more](https://manual.bubble.io/the-glossary#learn-more-33)[

Article: [The property editor](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/tabs-and-sections/design-tab/the-property-editor) Article series: [The Bubble editor](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor)​

Core reference: [Element properties](https://manual.bubble.io/core-resources/elements/shared-properties) Core reference: [Responsive properties](https://manual.bubble.io/core-resources/elements/responsive-properties)​

Repeating group


- A repeating group is a container element that lets you display a list of things from a data source
- This can be any type of data: [things](https://manual.bubble.io/the-glossary#thing-database) from the database, a list of texts, the results of an [API call](https://manual.bubble.io/the-glossary#app-connector-plugin) or any other array of data
- Repeating groups can be set up to be displayed horizontally, vertically and as a masonry grid
- You can place any kind of [element](https://manual.bubble.io/the-glossary#element) (like text and images) inside each cell of the repeating group, which can load data from the thing in that cell

Learn more](https://manual.bubble.io/the-glossary#learn-more-34)[

Article: [Repeating groups](https://manual.bubble.io/help-guides/design/elements/containers/repeating-groups) Article: [Finding data](https://manual.bubble.io/help-guides/data/the-database/finding-data)​

Core reference: [Repeating group properties](https://manual.bubble.io/core-resources/elements/containers#repeating-group)​

Responsive design


- Responsive design means to design your app to adjust correctly to different screen sizes and resolutions
- The goal of responsive design is to allow one page to be equally useful and visually pleasing on different devices such as computers, tablets and mobile phones
- Bubble has an advanced responsive engine that allows you to set up pixel-perfect design and responsive rules to control the behavior on different screens

Learn more](https://manual.bubble.io/the-glossary#learn-more-35)[

Article series: [Responsive design](https://manual.bubble.io/help-guides/design/responsive-design)​

Core reference: [List of responsive properties](https://manual.bubble.io/core-resources/elements/responsive-properties)​

Run as


- The *Run as* feature lets you preview your app as a specific user
	- This is useful to debug issues: you can see the app exactly as the user experiencing an issue does
- It's available in both preview mode and your live app
- You will find it in the *Data > App Data > "All Users"* table. It's a small text link next to the user data in the table.

Learn more](https://manual.bubble.io/the-glossary#learn-more-36)[

Article section: [Previewing your app / Run as](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/previewing-your-app#run-as-a-specific-user)​

Run-mode


- When you app is actually running and you have users engaging with it, i.e. when you're running your app, as opposed to editing it ([edit mode](https://manual.bubble.io/the-glossary#edit-mode))
- When you click *Preview* in the editor, Bubble opens up the app in run mode, just as if you had visited the URL of your app
- Both the "Development" version and the "Live" version of your app have run modes, i.e. if you are editing your app on the Development version and click "Preview", you will enter run mode of the Development version

Learn more](https://manual.bubble.io/the-glossary#learn-more-37)[

Article: [Previewing your app](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/previewing-your-app)​

SEO


- SEO, or Search Engine Optimization, is the practice of optimizing your pages to rank highly in search engines such as Google and Bing
- It's only needed for pages that you want users to find in search engines, and not for locked pages (pages requiring login for example)
- SEO is generally done in two places in Bubble:
	- The overall app settings
	- Each individual page

Learn more](https://manual.bubble.io/the-glossary#learn-more-38)[

The article series below goes into both the theoretical part of SEO and how to set it up in Bubble.


- Article series: [SEO](https://manual.bubble.io/the-glossary#seo)​

Signing up


- In this context, we mean signing up an account in your *app*, not signing up to a Bubble account
- Bubble features a built-in, secure sign-up system that lets users create an account and [log in](https://manual.bubble.io/the-glossary#login) using their preferred credentials
- Using [plugins](https://manual.bubble.io/the-glossary#plugin), you can also allow users to sign up using a third-party service like Google or Facebook

Learn more](https://manual.bubble.io/the-glossary#learn-more-39)[


- Article: [User accounts](https://manual.bubble.io/help-guides/data/user-accounts)​

SPA (Single-Page Application)


- A Single-Page Application (often abbreviated to SPA) is a way to set up your app's navigation as a single page, as opposed to navigating between pages
- This is done by hiding and showing elements on the page
	- This is predominantly done using the group element, and collapsing its width and height when hidden to make room for another group
	- This happens instantaneously, making the switch between groups unnoticeable for the user

Learn more](https://manual.bubble.io/the-glossary#learn-more-40)[

Article series: [Navigation](https://manual.bubble.io/help-guides/logic/navigation) Article: [SPAs](https://manual.bubble.io/help-guides/logic/navigation/single-page-applications-spa)​

Static data


- Static data in Bubble means data in your app that needs your app to be re-deplyed to be updated
- This includes
	- Option sets
	- App texts (translations strings)
	- Element data that's not the result of a dynamic expression (such as text in a text element)
- Static data like the ones mentioned above become part of your app's JavaScript code files, and should not contain any sensitive information

Learn more](https://manual.bubble.io/the-glossary#learn-more-41)[


- Article series: [Static data](https://manual.bubble.io/help-guides/data/static-data)​

Style


- Styles are collections of styling properties (colors, borders, fonts, etc) that can be saved, named and applied to multiple elements
	- Styles are bound to one element type (i.e. styles for buttons, styles for text)
- When you create an app, a default set of styles are automatically generated
- Styles help keep the look and feel of your app consistent and speeds up development
	- They also help you make updates to multiple elements at once across pages. Any change you make to a style is automatically applied

Learn more](https://manual.bubble.io/the-glossary#learn-more-42)[

Article: [Styles](https://manual.bubble.io/help-guides/design/styling/styles)​

Template


- A pre-built app that you can use as a starting point for creating your own app
- Can only be used when starting a brand new app, i.e. cannot be applied retroactively
- Usually includes a combination of pages, elements, styles, workflows, etc
- There's a large collection of community-developed templates available (see link below)
	- Some templates are available at no cost, while others require a one-time payment per application

Learn more](https://manual.bubble.io/the-glossary#learn-more-43)[

Page: [Templates](https://bubble.io/templates)​

Article: [Using templates](https://manual.bubble.io/help-guides/design/using-a-template)​

Thing (database)


- A database thing is a single record of any data type in your database
- For example, one user who signs up in your app is one database thing

Learn more](https://manual.bubble.io/the-glossary#learn-more-44)[

Article series: [Data](https://manual.bubble.io/help-guides/data)​

Core reference: [List of data sources](https://manual.bubble.io/core-resources/data/data-sources)​

Unique ID


- Every database thing in Bubble is automatically assigned a unique ID
- I'ts a 32-character string that follows the following format:
	- 1675853365035x879057409457629600
- You cannot change or delete a unique ID
- If you have a SQL database background, the unique ID is the *primary key* of database records in Bubble

Learn more](https://manual.bubble.io/the-glossary#learn-more-45)[

Article series: [Data](https://manual.bubble.io/help-guides/data)​

URL parameter


- A URL parameter is a way to pass and read data using the URL in the browser
- It follows a key-value format and starts with a "?" after the main URL.
	- For example, in "[my-bubble-app.com/page?navigation=user-profile](http://my-bubble-app.com/page?navigation=user-profile)", "navigation=user-profile" is the URL parameter
- URL parameters can be used to pass any kind of data, including custom [data types](https://manual.bubble.io/the-glossary#data-type) (by passing the [unique ID](https://manual.bubble.io/the-glossary#unique-id) of the thing you want to identify)
	- The upside of using URL parameters is that users can use the *back* button in their browser to return to the previous URL if needed, meaning that they can use the back button in a [single-page application](https://manual.bubble.io/the-glossary#spa-single-page-application)​
	- You set URL parameters using the go to page action, and the URL parameter is instantly applied without having to reload the page (if you are going to the same page the user is currently on).

Learn more](https://manual.bubble.io/the-glossary#learn-more-46)[

Article: [URL parameters](https://manual.bubble.io/help-guides/data/temporary-data/url-parameters) Article series: [Navigation](https://manual.bubble.io/help-guides/logic/navigation)​

Core reference: [To to page](https://manual.bubble.io/core-resources/actions/navigation#go-to-page-...)​

User


- Users are a built-in data type in Bubble
- They are also the only data type that come with some specific things:
	- A built-in email field
	- An authentication system (allowing users to securely [sign up](https://manual.bubble.io/the-glossary#signing-up) and [log into](https://manual.bubble.io/the-glossary#login) your app)
- You can set up [privacy rules](https://manual.bubble.io/the-glossary#privacy-privacy-rules) that govern what database data a user has access to
- If a user has not yet signed up, Bubble automatically creates a temporary user that you can save data to. That data is transferred to the user when they sign up on the same device.

Learn more](https://manual.bubble.io/the-glossary#learn-more-47)[


- Article: [User accounts](https://manual.bubble.io/help-guides/data/user-accounts)​

Version control


- Version control is a set of features that allows you to set up separate [branches](https://manual.bubble.io/the-glossary#branch) in the [Bubble editor](https://manual.bubble.io/the-glossary#editor-the-bubble-editor)​
	- These branches allow team members to work on separate features in isolation
	- Changes that you make in one branch will not be visible in other branches before they are synced

Learn more](https://manual.bubble.io/the-glossary#learn-more-48)[

Article series: [Version control](https://manual.bubble.io/help-guides/maintaining-an-application/version-control)​

Version-test


- The version-test is the preview version of your app
- You can see *version-test* in the URL when you preview your app:
	- [https://my-bubble-application.bubbleapps.io/](https://my-bubble-application.bubbleapps.io/)**version-test**/page
- The development environment has a separate, independent database from the live environment to help you test your app's features without affecting live data
- If you remove *version-test* from the URL, you will be taken to the live app instead (if your app has been deployed)

Learn more](https://manual.bubble.io/the-glossary#learn-more-49)[

Article: [Previewing your app](https://manual.bubble.io/help-guides/getting-started/navigating-the-bubble-editor/previewing-your-app)​

Workflow


- A workflow is the combination of an [event](https://manual.bubble.io/the-glossary#event) (such as a button-click) and one or more [actions](https://manual.bubble.io/the-glossary#action)​
- Workflows either belong to a specific page (and thus only run when a user is on that page) or is an API Workflow that can be run or scheduled server-side, or with an API call
- Workflows are what makes your app react to user interaction, including:
	- Making changes in the database
	- Hiding/showing elements
	- Navigating to another page or external site
	- Sending emails

Learn more](https://manual.bubble.io/the-glossary#learn-more-50)[

Article series: [Workflows](https://manual.bubble.io/help-guides/logic/workflows)​

Core reference: [List of events](https://manual.bubble.io/core-resources/events) Core reference: [List of actions](https://manual.bubble.io/core-resources/actions)​

Workflow API


- The Workflow API is a part of the Bubble API, and allows external apps and systems to trigger API workflows by making an API call to your app
- The Workflow API must be enabled in *Settings > API*
- The Workflow API lets you set up [API workflows](https://manual.bubble.io/the-glossary#api-workflows)​

Learn more](https://manual.bubble.io/the-glossary#learn-more-51)[

Article series: [The Bubble API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api) Article series: [The Workflow API](https://manual.bubble.io/help-guides/integrations/api/the-bubble-api/the-workflow-api)​

Core reference: [API workflow properties](https://manual.bubble.io/core-resources/api/the-bubble-api/the-workflow-api)​
