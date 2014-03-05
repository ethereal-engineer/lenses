# Lenses for Quoting

## Introduction

This list of lenses is a work in progress. It was compiled after a client project went waaaay over budget. It was not the first time that I've underestimated a project, so I started writing a list of questions that, if I had asked myself in the beginning, perhaps would have improved the accuracy of my estimate and reduced the size of the hole in my pocket. The lenses aim to provide not-so-much a checklist as a list of triggers that will help developers (especially me) burn themselves less often.

All relevant questions aim to get you thinking about your design and your estimate, because if you don't think first and plan ahead, you may wind up shooting yourself in the foot. Some aspects will not apply to all apps, but as [@insertjokehere](https://twitter.com/insertjokehere) recently noted at a Sydney CocoaHeads meeting, most apps these days require interaction with a server and some form of local data model. 

Note that the actor of the questions vary from time to time between I, you, the app etc. This *is* a work in progress. I intend to hone it, make it better, expand it, distill it and perhaps even write a series of answers to some of the questions posed. 

It is my sincere hope that the content of these lists helps you, the developer, the project manager, the wearer of many hats, in at least some small way, to make a better and more peaceful life for yourself.

## The Lenses

There are likely many duplicates in the following lists and the categorisation is somewhat ad hoc. Pull requests are more than welcome, but I will attempt to improve them as I find different combinations of questions more beneficial.

### Project Management

1. How will I monitor and police my quote to ensure that my efforts remain in the scope of it?
1. What amount of time should be added to each task for time tracking and management?
1. How much time will I spend doing high-level management of the project such as version planning, viewing reports, tweaking estimates and generally keeping the project on-track?
1. Am I micro-managing?
1. How long will it take to lay out the project into my project management system (e.g. JIRA, Confluence etc)?
1. How long will I spend breaking up the project into milestones and deliverables?
1. How long will it take for me to incorporate the client or project into my management, billing or other systems?
1. How long will I (did I) spend putting together the quote?
1. How much time will be spent maintaining the management systems for the project (e.g. JIRA, Confluence, Bamboo)?

### Uncharted Territory

1. Which areas of this project (of all kinds) will require research, learning or otherwise I have not done something exactly like this part before?
1. Which items will be embracing new technologies to me?
1. What sort of margin should I apply to items that embrace new technologies or require research?
1. Which items have I never used in a production environment before?
1. What parts of this project have I actually never done before (project management, new tools, new components, new technologies, new approaches, new methodologies)?
1. Are there older, more familiar techniques, approaches, tools, etc, that I could use instead or could fall back on?
1. Have you ever dealt with this kind of server communication explicitly before? Have you ever used the components for it that you have decided to now use before?
1. How long do you need to revise all the technologies that will be used by the project such that you can be counted on as an expert in them for the project?

### Assumptions

1. What questions do I have about this project that I might be tempted to just "see how I go with it"?
1. How many items have I made assumptions about in how they will work and not consulted with the client?
1. Have I listed all assumptions in written form and had them agreed upon by the client?

### Help

1. Do you know who to turn to in the Cocoa community if certain parts of the project go sour or stump you?

### Thought Provokers

1. How could I estimate this better?
1. How much time have I already spent estimating this? Am I doing too much or too little?
1. Have I allowed myself to complete this project at a pace that will not lead to inevitable burnout?
1. Have I allowed myself enough time to complete this project at a code quality that I would like to identify myself with?
1. Will any purchases of tools be required for this project? Could purchase of tools improve the overall estimate?

### Emotional Influence

1. Do I feel pressured by the client's assurances that it will be alright? Or by the client's reputation or importance?
1. Do I feel in control of my life?
1. Do I feel in control of this project and at ease with all details of it?
1. Have I made an unconscious or conscious decision that if I am wrong I will "just work harder" to compensate?
1. Am I cutting corners in this estimation because I am impatient, bored or desperate for cash?

### Time Planning

1. Have I allowed for parts of my personal or business life that may conflict with the project (e.g. sickness of family members, birthdays, holidays, social commitments, professional meetings or commitments)?
1. Have I allowed for public holidays, weekends, sick days and my general stamina?
1. How many hours per day am I intending to work towards this project?
1. Has the client expressed any particular time constraints for the project? In order to meet those constraints, will I need to subcontract?
1. Is there any research that I have to do for this project that is not billable to the client (e.g. legal conditions or clauses, financial obligations etc)?

### Planning Ahead For Enjoyable Development

1. How long do I want to spend writing commit notes per day?
1. How much time will I spend documenting the code and techniques during development?
1. How much time will I spend documenting the code and techniques after development?
1. How much time will I spend reviewing warnings and tidying up before releases?
1. How often will you run OCLint on your code?
1. How often will you run the static analyser in deep mode on your code?
1. Have you allowed time for lag when running 'pod install'?

### Communication & Feedback

1. How much time per day do I expect to be communicating with the client (this leans heavily on how concrete the specification is to begin with, as well as the available methods of communication)?
1. How many questions do I have about the spec right now? Have I listed them all and asked for clarification?
1. How will the client give me feedback?
1. How will the client see progress in the project?
1. Will the client need to report issues into JIRA?
1. Over the course of this project, who will I be communicating with?
1. How often will you be interacting with client feedback and direction on the app? How long will this kind of a process add to the estimate?

### Error Margin

1. How confident do I feel about the accuracy of the quote (the less confidence, the larger the error margin should be)?
1. How rushed am I in making this quote? Am I being thorough?
1. How much of an error margin should I add to this project for my level of experience?
1. What margin am I allowing for general refactoring (note that more time should be spent on the design before coding to reduce this as much as possible)?
1. How much time has been allotted for the chance "impossible" bug? And how likely is such a bug on this project?
1. How much time has been allotted for filing radars?
1. Has the warranty period been budgeted for?
1. How will you deal with late crystallising specifications or late additions of features? Is a margin really enough or should you negotiate such features and changes in the price at the time?

### Strategy

1. Will I lay out the entire UI first so that the client has maximum tangibility as I make things work or will I make complete sections at a time?
1. How will I inform the client if more money is required? Is this even an option?
1. How will I inform the client if the project is running late?
1. How will I avoid "feature creep"?
1. How will you deal with misunderstandings in the spec if they are your fault?
1. How will you deal with misunderstandings in the spec if it is the client's fault?
1. How will you deal with assumptions made on the client's side of things that turn out to be incorrect or misguided?
1. How will you deal with features that the client has assumed will be included but you have not budgeted for?
1. What will you do if the client has omitted a detail in the specification that causes a blow-out in time spent?
1. What will you do if the client has omitted a detail in the specification that you catch before you start work on it?
1. How will I ask for payment? How will payment be made? Have I calculated the correct tax component? How will that be handled?
1. What will your policy be for late changes in the spec?
1. If you realise only when you are developing it that you lack information about a particular aspect of the design, what will your approach be?
1. If you make suggestions for improvement to the design, will you absorb the cost or add it to a separate quote?

### Opinion

1. How will I organise my personal recommendations and notes on tasks and keep them separate from actual requirements?

### Testing

1. Will I need to manage a test group and their respective feedback?
1. How will Core Data model changes be handled by beta testers? Do I need to auto-migrate or just warn to delete the app each time?
1. At what stage will the app be ready for testing?
1. Have you tested with more than one user account for signing in and signing out (and are all details preserved and removed as required)?
1. How much time have you set aside for full regression testing?
1. Have you written up a test plan for each release? How long will it take to perform each time?
1. How much time will you spend testing your app personally, as a user, per release?
1. Will you be using state restoration? Have you set aside time to test for state restoration from all screens?
1. Will you be using background updates? Have you allowed for the time needed for testing?
1. Will you be using push notifications? Have you allowed for the time needed for testing?

### Payment, Deliverables, Distribution

1. How will milestones be confirmed?
1. How will the product be deployed?
1. In how many increments will the product be deployed?
1. Will each deployment require detailed change notes?
1. How often will the client expect to receive a new version? How much time should I allow for delivery of each version?
1. Is upload time a factor?
1. Will I be handling submission to the App Store?
1. Will I be writing the App Store copy? What style would the client like?
1. Does the client have their own iOS Developer account?
1. How will the source code be delivered?
1. How will progress be measured by the client?

### Administration

1. Does the client need a JIRA login?
1. Is HockeyApp or TestFlight maintenance required?
1. Is UDID registration and maintenance required?
1. How long will be required for certificate and provisioning profile management?
1. Which devices will I need to test all screen sizes and orientations (esp. for provisioning)?

### Setup & Teardown

1. Is a special repository setup (e.g. a double-headed repository) required?
1. What kind of access does the client need to the source code?
1. What debugging tools will need to be included in the project?
1. How will I ensure debugging tools and logs do not make it into the released product?
1. Which unit testing tools should I set up?
1. How long will it take for me to set up my initial project including all targets and the pod file?
1. Is mogenerator required?
1. Do I want to add any extra targets?
1. Have I included time to set up an AppleDocs target?
1. Will I be spending any time tweaking the build settings?
1. Will I need to set up an automatic build number incrementing script?
1. How long will it take to set up repositories, the initial Xcode project etc?
1. Have you allowed time to set up appropriate build scripts for things like AppleDocs, OCLint and Mogenerator?
1. How much extra time will need to be spent writing technical documentation?

### General

1. Will any other developers be working on the project?
1. What iOS versions will be supported? This adds a multiplier to the whole project.
1. What devices will be supported? Again, multiplier.

### Working From A Spec

1. Will the client be providing a design, a spec, artwork and other resources?
1. How much of a margin for error should I allow based on the level of completeness of the spec?
1. What have I assumed about the way things work from the spec that could possibly be different?
1. Is any part of the design or specification incomplete or assumed?
1. Have I marked any items on the spec that I am concerned about?
1. Have I marked any items on the spec that will be new areas of development or technology for me?
1. Does the specification or design have any logical errors or things that would not be plausible with the available server API or development tools?
1. How much of the design or spec has been left up to you? How much time have you allocated to experimentation, design, research, advice, communication, discussion, disagreement, resolution and time zone differences?
1. Have you done your best to make all recommendations for improvements in the design before starting the project?

### Vendor Code & Attribution

1. For each vendor component, have I estimated enough time that I could easily write my own version if required?
1. How confident am I that each vendor component will fill the need in this project?
1. How much time will I need to play with each vendor component before I decide on which ones I will use?
1. Do I need to credit any of the vendor component authors? How will I do it?
1. How much time will I need to review the license conditions of the vendor components?
1. Does the app need a Settings.app bundle (for attribution or otherwise)?
1. How much time has been allotted for issues with vendor code?
1. How much do you trust the core components that your app is designed/built on - have you allowed time in case of failure of any of them?
1. How long do I intend to spend searching for vendor solutions before writing my own?
1. Have you attributed all vendors as required by their respective licenses?

### The Client

1. How professional is the client's documentation of their API?
1. Is it possible that there are errors in the client's API documentation?
1. Is anything missing from the client's API documentation?
1. What will I do if the client's API documentation is wrong or if I spend time on an issue only to discover that it's their server's fault?
1. How much time have you allowed for issues that take time from the project only to realise that they are caused by client misinformation or client's server?
1. Is it possible that the client has incorrect information in their documentation or specs? How much time have you allowed for this?
1. Has the client made any special requests?

### User Experience

1. Have I read the HIG lately?
1. How will the app present feedback to the user?
1. Will the app use blocking modals or process requests in the background? Or a mixture of both? Have I listed them?
1. How will errors be presented to the user?
1. How can I avoid annoying the user if there are lots of errors?
1. What options should I give the user for recovery of errors?
1. If a user has unsaved changes to a form or other item, how will the app prompt them if they navigate away or cancel?
1. How will the app preserve user input in case of app termination?
1. What is the default option/settings setup for the app, as per the client's spec or request?

### Core Data

1. Do I need to include a data migration plan and time for testing?
1. Will I use Magical Record or build the stack myself?
1. What *minor* change would shift this design from not requiring Core Data to being an excellent candidate for it? How likely is that change to occur?

### UI

1. Does this app lend itself to storyboards, nibs, Masonry or a mixture? Consider the time savings of each approach and the code bulk.
1. Have I noted the more complicated view constructions?
1. Will I be using segues or pushes or both?
1. Will I be using unwind segues or pops or both?
1. Have I drawn out the flow of the app on a whiteboard?
1. How many orientations will the app support and how will this affect the implementation time?
1. How much time will I need for orientation testing?
1. How many different screen sizes are supported and how will that affect the implementation time?
1. How much time will I need to test all screen sizes and orientations?
1. For each screen, how long will it take to build and arrange the visual elements?
1. For each screen, how will a user interact with it (list the ways)?
1. For each screen, is user input required?
1. How will the keyboard be handled?
1. Does any of the input require validation?
1. Does any of the input or choices change the available choices or validity of other input?
1. Is a special keyboard required?
1. What about a bluetooth keyboard?
1. Have I drawn out every possible user interaction on a whiteboard?
1. Are any user-interactions not natively supported or custom?
1. Have I not dealt directly with implementing any of these user interactions, screens, input methods, controls, animations or movements before?
1. Are any of the app's movements, animations, flourishes etc not natively supported or custom?
1. How long will it take for me to adjust each screen element to match the designer's font, colour, size and alignment?
1. Which elements in the design are not entirely standard?
1. Are there any non-standard animations or transitions that would require extra time to design/build/test/tweak?
1. How much time have you put aside for super-small finicky pixel tweaks, alignments, animation timing adjustments etc?
1. How will the app keep the most current and valid information on all visible screens at all appropriate times (refreshing, caching, object counts, statistics)?
1. What would happen to your user interface if the app was subject to a slow connection or an impatient, hyperactive user?
1. Are standard components being used in non-standard ways in the design? How will you deal with that?
1. How much time do you expect to spend "skinning" the app?
1. Have you designed your auto layout to incorporate orientation or required size changes?
1. Do any standard visual things interfere with the design?
1. Will any of your views need to scale dynamically for the content?
1. How will you present loading progress to the user?
1. How will the different statuses of visual items be depicted to users (how many conditions are there, loading state, etc)?
1. When will requests be made to the server/API Client in coordination with the user interface (i.e. before the user taps, after the user taps, before a page loads, before a page is pushed onto a navigation stack etc)? How will this affect the flow of the UI?
1. How many form editors are required?
1. How will you handle date editing?
1. How will you handle option picking?
1. Does option picking require options that will not be provided by the server (such as deselecting all options or "none")?
1. How will you manage boolean options?
1. Are nested options a requirement?
1. Will your progress UI element handle a user who doesn't wait for it to finish before attempting to continue?
1. In the case of a tabbed layout, will you use a single table object with multiple datasources or multiple table objects?
1. Has the designer provided a stylesheet of all fonts, colours and sizes used throughout? If not, how much time have you allotted to matching these?
1. What tools will you use to align your design to match the designer's design? How important is pixel perfection to the client?
1. Will you be handling user login validation? How will you handle invalid login attempts?
1. Have you allotted time for the very important first user interaction such that it is ultra smooth?
1. What apps does this app resemble and which paradigms will be borrowed or stolen?
1. Will your app block the UI modally when API requests are made or perform them in the background?
1. Will you provide your user with the ability to cancel requests? How will this work?
1. How will you show progress when progress is unmeasurable (e.g. slow DNS, streaming content, unknown content size)?
1. How will you handle change management from the app to the server? Will changes be sent instantly or in batches? Will they be sent explicitly or implicitly? How does this affect the flow of the app?
1. When making volatile changes, how will this be presented to the user?
1. How long have you set aside to build each kind of reusable cell (including cell options, expansions, auto layout rules, selection behaviour)?
1. Will any of the tables in your UI allow user manipulation (i.e. reordering or deleting)?
1. Will you be allowing in-place editing for cells in your app? Will this happen at any time or only when in a modal editing view? How will you handle the user navigating away from unsaved changes?
1. If you are building a table-centric UI, what will you use as the base object for your datasource items? How long have you allowed for constructing this additional data model of datasource items?
1. If dealing with offline data, how will you relay the offline status of the app to your users? Will the UI be required to respond to the connectedness of the app? How will this affect the development and test plan?

#### For Each Screen

1. Are any screen arrangements or alignments familiar, yet not entirely standard?
1. How will each screen be implemented/constructed (storyboard, nib, datasource, auto layout, view-based, in code)?
1. When the user first sees this screen, what will they see?
1. How will the app provide feedback to the user for form validation?
1. What transitions and modality will be used?
1. Which screens belong to which navigation controller/path?
1. For each screen, should any control automatically become first responder?
1. For each screen, what kind of validation or form logic is required?
1. For each screen, is any custom animation required?
1. Have you designed the layouts for extra long text display?
1. What is the policy for extra long text display? Will it ellipse? Will it wrap? Will it shrink font size?

##### For Each User Input

1. Do I need to consider default values for inputs?
1. For each text input control, what should the keyboard's return key be?
1. For each text input control, what should the next control be?
1. For each text input control, what should the spellcheck and capitalisation scheme be?
1. For each text input control, what kind of keyboard should be used?
1. Is email address or other regex-based validation required?

### System Design

1. Do I have any questions for the client in relation to their spec or existing systems?
1. Which questions for the client should be addressed before starting the project design?
1. To what level of detail should I design the system before starting work?
1. Have I drawn out the block diagram of the app in sufficient detail?
1. Will any of the block diagram entities be using queues?
1. Will the system need to handle pagination?
1. What happens if the user has no internet connection?
1. How will the app reconcile local changes with pagination?
1. How often will the app make requests to the server?
1. How will the app sync local changes with the server and vice versa?
1. How will the app handle errors?
1. How will each object in the block diagram handle errors?
1. How many user preferences need to be stored?
1. How many pieces of secure information need to be stored?
1. What happens if credentials are stored in the iOS keychain and the user deletes the app and reinstalls it?
1. What should happen when the user logs in?
1. What should happen when the user logs out?
1. What events should trigger a refresh of data from the server?
1. Are any aspects of the design assumed or ambiguous? How could these go wrong?
1. Have you allowed time to design your iOS Keychain scheme?
1. Have you allowed time to design your iOS NSUserDefaults scheme?
1. Will you need to use iCloud?
1. Will your app error system create errors that are fully-formed and passable to the user at first instance (i.e. with full information and recovery suggestion dictionary) or will they be translated at the time that they are presented to the user? How will this affect your code base?
1. Is any part of the design or specification incomplete or assumed?
1. How long have you allotted for local data model design? Do you know which tool you will be using to represent the design? How likely is the design to one day be converted to Core Data or similar?
1. Have I considered user security in all aspects of the design?
1. Have I considered user experience in all aspects of the design?
1. How long will it take for me to sketch out a basic system design?
1. How long will it take for me to enhance the basic system design into a full system design?
1. How will you handle change management from the app to the server? Will changes be sent instantly or in batches? Will they be sent explicitly or implicitly? How does this affect the flow of the app?
1. How will you communicate changes in data from the data model to the UI?
1. How long have you set aside to build the various (table, collection view) datasources that the app will require? Have you laid them out in a design plan or set aside time to do so? Do the allow both static and dynamic elements if required?
1. Will this be a universal app or a separate app per device supported? Will the app have to support other devices in future? Should shared code or libraries be used?

### Existing Code

1. Have I carefully examined the existing sourcecode if any?
1. Does the existing sourcecode run correctly on all intended platforms?
1. What is the smell of the existing sourcecode like?
1. How long will any changes I make take to integrate into the original app?
1. Is there any existing source code, examples or similar projects that you might be able to gain advantage from analysing?

### Resources

1. Do I need to work with Photoshop, Slicy or other to obtain art resources from PSD files or will they be provided for me?
1. If art resources are missing, who do I contact to get them?
1. Am I able to make requests from the client's worker resources (such as a designer)?

### Localisation

1. Have I included sufficient time for localisation of the storyboard, nibs and code string files?
1. Is local localisation of user-facing text required (there's always some) or will it be managed by the server?

### API Client

1. How will the API client work with the UI to inform users of progress (and which technical mechanisms will be used)?
1. How much time should I allocate to testing with various levels of poor network connectivity?
1. Should I proactively work with Reachability to test the user's current connectivity?
1. What events will cause the app to pull down data from the server?
1. What events will invalidate local data, requiring new data from the server?
1. How much time have you allowed for poor network connection testing for your entire app?
1. How important is order to the client? What order should items be displayed in and how will you manage that?
1. Is local sorting of items required or will this be managed by the server?
1. Are there any limitations with the server's current implementation? How will it affect your design?
1. Have you made any assumptions about the server's current capabilities?
1. Have you carefully read all the server API docs (if plausible)?
1. How will you prevent the user from making double requests?
1. How will you present loading progress to the user? (not a duplicate, as this affects design here too)
1. Should all data be refreshed from server or just a portion?
1. Does the server support partial refreshing?
1. Will you be handling session management for the API? What happens if a session token becomes expired? Will your API automatically log the user back in? Have you allotted time to build this feature? How will this affect the complexity of the API client?
1. Have you allotted enough time to play with the server API and fully understand it (including all get and all put requests)?
1. Have you allotted enough time to resolve some issues with the server API?
1. How will the API client deal with slow or poor network connections? Will it check MD5 sums or sizes?
1. How will the app ensure that invalid (partial) downloads are known to be such?
1. What will the API client do when there is no internet connection? Will it cache requests or ignore them or return an error?
1. Does the server use UTF-8, UTF-16 or other encodings?
1. Will your app be required to connect to servers sporting self-signed SSL certificates? How will you deal with that securely?
1. Will your app block the UI modally when API requests are made or perform them in the background? (not a duplicate)
1. Will you provide your user with the ability to cancel requests? How will this work? (also not a duplicate)
1. If performing in the background, how will you deal with limiting requests (or cancelling those that are no longer needed) so that multiple NSURL loader requests don't block the main thread?
1. Will you have a blanket message for all API errors or will you address each error code individually or somewhere in-between?
1. Will you be dealing with compressed server responses? Is there anything special that you need to consider for those?

### Unit Tests

1. When will I write the unit tests?
1. Which unit tests are most important?
1. Have you allowed time for unit tests on bad server responses?
1. Will you be running your unit tests manually or delegate them to a build server? How long will this add to each release?
1. How much time have you set aside for unit test writing and maintaining unit tests once the code they are based on changes?
1. Have you considered writing automated UI testing?
1. How much time have you allocated for unit testing the API client alone?
1. How much time have you allocated for unit testing the correct import/export of server API objects to local objects?
1. How often will you run your unit tests? Will you run a build server? If so, how long will setup and configuration of the project/server take?
1. Will you add unit tests for any errors or crashes that come up under warranty? Have you allocated time for this?

### Performance Enhancement & Polish

1. How much time have you allotted for smoothing visual performance such as scrolling and transitions?
1. How much time has been set aside for fine-tuning screen layouts, transitions, animations and the like (i.e. "polish")?

### Prototyping

1. How much creative license have you been given?
1. How much time has been allotted for visual experimentation?
1. How much time has been allotted for cleaning up once experimentation is done?
1. If building from a prototype, how long will it take to translate each prototype view controller (i.e. FAT view controller) into a slim view controller (as few as possible) and required datasources?

### Offline Storage / Local Data Model

1. If paginating and a refresh is required, or local changes are made (records added or deleted) how will you deal with it?
1. How will you clear the local data storage on sign out and guarantee user separation on user sign in?
1. When will the local storage be maintained or emptied?
1. Will local storage be backed up on iCloud/iTunes?
1. How will you deal with corrupt records from app termination or crashes?
1. Will you use NSFetchedResultsController? If so, how will you ensure that your UI table is not flooded with background updates?
1. Will you base your UI on local storage and have the API client add to said local storage from server responses or will you only show local (offline) storage if the API request fails? How will this affect the UI design? How will this affect the overall system design?
1. How will you keep the locally stored data up-to-date with the server data?
1. Will you be required to reconcile synchronisation conflicts? What will the policy be?
1. How will you prevent duplicate entities?
1. How will you know when to completely replace a local data object as opposed to simply appending items to it (i.e. how will you know when the server response represents an authoritative and complete data model object)?
1. How will you deal with server constants (i.e. where will they be defined? Should they be easily updatable? Is a consts header file good enough)?
1. How will you represent singleton items in the server's data-model (e.g. a user may have only one user "account")? Is it possible that the singleton status may change in future?
1. Will you use a Core Data data model or another kind of object data model or a combination of both?
1. Will you have to delete temporary files or user document files when the user signs out?
1. How will your app deal with local pagination? Remote pagination? Does it work well with your synchronisation policy?

### Searching

1. If you are required to include a local search in your app, what kind of search methodology will you use? 
1. How detailed will your search be required to be?
1. Will it match entire phrases or each word? 
1. Will it be inclusive (OR) or exclusive (AND)?
1. Will it have configurable options? How will they be presented to the user? 
1. Will the mobile device be able to handle your most complex search without impacting the UX? 
1. Will you start searching immediately or after a few characters? 
1. Will you use a live search or wait for the user to hit a button?

### Analytics

1. Have you set aside time for lag in analytics reporting?
1. Have you set aside time for a comprehensive and insightful analytics reporting (and naming) scheme?
1. Have you set aside time for analytics testing?

### Value

1. What suggestions could I make for the project and offer to the client as an optional extra cost?

### Not Related To Time So Much (But Handy)

1. How will the project be versioned?
1. Would an automated CI help or hinder?
1. What will the app's tint colour be (very much an identity and branding question)?
1. What should the title of the cancel button be on error-based alerts?
1. Will the app use bar button text or icons or both? How will this work in other languages?
1. Have I checked that my project is set up with relative paths? Have I tried checking it out and compiling it?
1. Will the client pay any incurred transaction fees?
1. Will the client pay for any required tool purchases?
1. Will you be committing your CocoaPods in your source repository or enforcing that all developers must have CocoaPods installed?
1. Have you set up your .gitignore properly for the project?
1. What is the net arrangement for payments?
1. Are all standard terms and conditions acceptable to both parties and reviewed by a legal representative?
1. Does the client have to pay GST?





