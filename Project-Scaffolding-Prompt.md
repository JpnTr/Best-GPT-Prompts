Create a [projecttype] (e.g., iOS app, web app, backend API) using [lang] and [framework] with [packagemanager] for dependency management. The project, named [projectname], should integrate [primaryapi] for [corefunctionality] (e.g., video generation, text processing), use [backend] as the backend, and implement [monetizationsystem] for a [monetizationmodel] (e.g., credit-based system, subscription). The project should follow a clean, modular, component-based architecture with small, editable files and a [uitheme]-themed UI with [uidesignelements] (e.g., gradients, animations).
Project Requirements
Core Functionality

Users can [useraction] (e.g., input text, upload files) on the main interface, which is processed by [primaryapi] to produce [output] (e.g., generated video, processed data).
A results interface displays the [output] with options to [outputactions] (e.g., save, share).
Each [coreaction] consumes [monetizationunit] (e.g., one credit, one API call).

UI Design

Use [framework] to build a modern, responsive interface.
Implement a [uitheme] color scheme with [uidesignelements] for a [uidescription] look (e.g., sleek, minimal).
Main interface: [maininterfacecomponents] (e.g., text input, submit button).
Results interface: [resultsinterfacecomponents] (e.g., output display, action buttons, navigation).

Folder Structure

Organize the project with a modular structure: separate folders for [folderlist] (e.g., Models, Services, Views, ViewModels, Utilities).
Keep files small and focused (e.g., one component or service per file) for readability and maintenance.

Backend with [backend]

Use [backend] for:
[authmethod] (e.g., anonymous authentication, email login) to manage user identities.
[databasetech] (e.g., PostgreSQL, MongoDB) to store [datastored] (e.g., user data, transaction history).
[backendfunctions] (e.g., edge functions, serverless endpoints) for:
Handling [primaryapi] calls securely.
Managing [monetizationunit] deductions and updates.
Processing [monetizationsystem] webhooks for [monetizationaction] (e.g., purchase validation).




Deploy [backendcomponents] (e.g., database schema, functions) via [backenddeploytool] (e.g., CLI, dashboard).

Monetization with [monetizationsystem]

Integrate [monetizationsystem] to manage [monetizationmodel] (e.g., in-app purchases, subscriptions).
Users purchase [monetizationunit] (e.g., credits, subscription tiers) to enable [coreaction].
Store and update [monetizationdata] in [backend]’s [databasetech].
Validate [monetizationaction] via [monetizationsystem] webhooks in [backend]’s [backendfunctions].

Dependencies

Use [packagemanager] to manage dependencies (e.g., [dependencylist]).
Avoid large third-party libraries to keep the project lightweight.

API Integration

Use [primaryapi] (key: [primaryapikey]) to perform [corefunctionality].
If [primaryapi] requires an alternative API (e.g., [alternativeapi]), use that with proper authentication.
Handle API responses asynchronously and display errors gracefully in the UI.

Performance and Best Practices

Ensure scalability and maintainability with a component-based [framework] architecture.
Optimize for performance (e.g., [optimizationtechniques]).
Handle edge cases like [edgecases] (e.g., network failures, invalid inputs).
Use [asyncmethod] (e.g., async/await, promises) for API and database operations.

Setup Instructions

Assume [backend] is configured with [authmethod], a [databasetable] (columns: [tablecolumns]), and [additionaltables] (columns: [additionalcolumns]).
Replace placeholder API keys for [primaryapi] ([primaryapikey]), [backend] ([backendurl], [backendkey]), and [monetizationsystem] ([monetizationkey]) with real keys.
Deploy [backendcomponents] via [backenddeploytool].

Deliverables

A fully functional [projecttype] with the described features.
A clean project structure with concise, well-documented files.
A [uitheme]-themed UI with [uidesignelements], built in [framework].
Integration with [backend] for [backendfeatures] (e.g., auth, database, functions).
[monetizationsystem] for [monetizationmodel], synced with [backend].
[corefunctionality] using [primaryapi] (or [alternativeapi] if needed).
Instructions for setting up API keys and [backend] in a README.

Notes

Prioritize simplicity and readability in the implementation.
Avoid generating code unless explicitly requested; provide a high-level plan or pseudocode if needed.
