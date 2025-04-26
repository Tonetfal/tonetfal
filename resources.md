# Unreal Engine Resources

It's a set of links to articles, documentation, and plugins I find useful.

<hr>

<details>
<summary><a href="#quality-of-life">Quality of Life</a></summary>
<br>

| Name                                                                                                             | Description                                    |
|:-----------------------------------------------------------------------------------------------------------------|:-----------------------------------------------|
| [Blueprint Assistant](https://www.fab.com/listings/14d7ba87-a587-406d-9369-ed75fa0a55ed)                         | Auto format blueprints                         |
| [Node Graph Assistant](https://www.fab.com/listings/525a33bb-9b05-405d-bf3e-42ca990fb31b)                        | Quicker interaction with nodes                 |
| [Linter](https://www.fab.com/listings/91946343-2304-4261-9743-7b8cb9e0f9b0)                                      | Force naming convention for your editor assets |
| [UE4Minimal](https://github.com/Sythenz/UE4Minimal)                                                              | Minimalistic nodes theme                       |
| [Map Foreach](https://github.com/MajorTomAW/ForEachMap.git)                                                      | Foreach node for Map                           |
| [Tonetfal Utilities](https://github.com/Tonetfal/TonetfalCommonUtilities)                                        | Additional blueprint nodes                     |
| [Weighted Random](https://github.com/ronaldburns/WeightedRandom)                                                 | Make randomization easier                      |
| [Channel Machine](https://github.com/Kranox21/ChannelMachine)                                                    | Texture packing and unpacking in the engine    |
| [Actor Component Timelines](https://www.fab.com/listings/dcae9d59-ec20-401d-b21c-4e5f5ef0a031)                   | Create timelines in actor components           |
| [Subsystem Browser Plugin](https://github.com/aquanox/SubsystemBrowserPlugin)                                    | Investigate subsystems from the editor         |
| [Console Variables Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/console-variables-editor) | View and modify console variables from a menu  |
| [Gameplay Tags](https://www.tomlooman.com/unreal-engine-gameplaytags-data-driven-design/)                        | Better enums                                   |
| [Component Picker](https://github.com/gregorhcs/UEComponentPicker)                                               | Pick components from details panel             |

</details>

<details>
<summary><a href="#cpp">C++</a></summary>
<br>

| Name                                                                                                                                      | Description                                                                                                                         |
|:------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------|
| [C++ Speedrun](https://landelare.github.io/2023/01/07/cpp-speedrun.html)                                                                  | Quick introduction to Unreal Engine C++ for people familiar with the language                                                       |
| [Common Issues & Tips](https://tackytortoise.github.io/2022/06/24/common-slacker-issues.html)                                             | Common C++ issues and how to avoid them                                                                                             |
| [Live Coding](https://dev.northstarhana.com/Unreal-Engine/Stop-Live-Coding)                                                               | Be aware of live coding and hot reloading                                                                                           |
| [UE5Coro](https://github.com/landelare/ue5coro)                                                                                           | Unreal Engine coroutines                                                                                                            |
| [UE5FSM](https://github.com/Tonetfal/UE5FSM)                                                                                              | Finite State Machine mimicking behavior of [Unreal Engine 3's FSM](https://docs.unrealengine.com/udk/Three/UnrealScriptStates.html) |
| [UPROPERTY/UFUNCTION/Etc](https://unreal-garden.com/docs/)                                                                                | Description of all the specifiers used for classes, structs, properties, functions etc.                                             |
| [Delegates](https://unreal-garden.com/tutorials/delegates-advanced/)                                                                      | Learn how to create event-driven code in unreal                                                                                     |
| [Developer Settings](https://unreal-garden.com/tutorials/developer-settings/)                                                             | Expose settings to Project Settings                                                                                                 |
| [Component Pointer Fixer](https://github.com/Duroxxigar/ComponentPointerFixer)                                                            | Helper utility to fix broken actor component pointers                                                                               |
| [Improved logging](https://github.com/itsBaffled/dbgLOG)                                                                                  | Move on from UE_LOG() to something better                                                                                           |
| [Garbage Collection](https://mikelis.net/memory-management-garbage-collection-in-unreal-engine/)                                          | Learn how the engine handles memory                                                                                                 |
| [Rider Templates](https://github.com/Tonetfal/Rider-Templates-UE5)                                                                        | Custom templates for basic Unreal classes to have a faster start when creating new classes                                          |
| [Save Game](https://www.tomlooman.com/unreal-engine-cpp-save-system/)                                                                     | Save your game progress                                                                                                             |
| [Serialization Best Practices](https://dev.epicgames.com/community/learning/talks-and-demos/4ORW/unreal-engine-serialization-best-practi) | Best practices to serialize your game data                                                                                          |

</details>

<details>
<summary><a href="#blueprints">Blueprints</a></summary>
<br>

| Name                                                                                                                                            | Description                                     |
|:------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------|
| [Pure & Impure functions](https://medium.com/unreal-engine-technical-blog/pure-impure-functions-516367cff14f)                                   | Difference between pure and impure functions    |
| [Function binds](https://unreal-garden.com/tutorials/choosing-function-in-editor/)                                                              | Treat functions as variables from details panel |
| [Custom nodes](https://www.gamedev.net/tutorials/programming/engines-and-middleware/improving-ue4-blueprint-usability-with-custom-nodes-r5694/) | How to create custom fancy nodes in C++         |
| [Custom thunk](https://gist.github.com/intaxwashere/e9b1f798427686b46beab2521d7efbcf)                                                           | "Templates" for blueprints                      |

</details>

<details>
<summary><a href="#networking">Networking</a></summary>
<br>

| Name                                                                                                                                                           | Description                                                           |
|:---------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------|
| [Client-Server Game Architecture](https://www.gabrielgambetta.com/client-server-game-architecture.html)                                                        | Theory for client-server game architecture                            |
| [How to Understand Network Replication](https://www.youtube.com/watch?v=JOJP0CvpB8w)                                                                           | Replication overview                                                  |
| [Multiplayer network compendium](https://cedric-neukirchen.net/docs/category/multiplayer-network-compendium/)                                                  | Starting point for multiplayer programming                            |
| [Multiplayer tips and tricks](https://wizardcell.com/unreal/multiplayer-tips-and-tricks/)                                                                      | Best practices for multiplayer                                        |
| [Persistent data](https://wizardcell.com/unreal/persistent-data/)                                                                                              | Handling data upon travelling                                         |
| [Connection arguments](https://unrealcommunity.wiki/passing-arguments-to-server-during-connection-cgxei5q3)                                                    | Pass custom arguments on connection                                   |
| [Beacons 1](https://docs.unrealengine.com/en-us/Gameplay/Networking/OnlineBeacons)                                                                             | Lightweight server-client interaction without normal world connection |
| [Beacons 2](https://forums.unrealengine.com/t/onlinebeacons-tutorial-with-blueprint-access/100043)                                                             | ^                                                                     |
| [Beacons 3](https://answers.unrealengine.com/questions/467973/what-are-online-beacons-and-how-do-they-work.html)                                               | ^                                                                     |
| [Beacons 4](https://forums.unrealengine.com/t/party-beacon-how-does-it-work-o-o/65824)                                                                         | ^                                                                     |
| [Custom struct serialization](https://www.aclockworkberry.com/custom-struct-serialization-for-networking-in-unreal-engine/)                                    | Serialize and replicate structs to optimize network                   |
| [Character Movement Component](https://docs.google.com/document/d/1UO6Ww6Lfpti3YElVdo9uioTUtQJQ9CoSLvd9kF8hvJo)                                                | Character movement component architecture                             |
| [Character Movement Component (Youtube)](https://www.youtube.com/watch?v=dOkuIvKCvpg&feature=youtu.be)                                                         | Character movement component explanation series                       |
| [Character Movement Component: Paragon](https://dev.epicgames.com/community/learning/knowledge-base/15El/unreal-engine-a-holistic-look-at-replicated-movement) | Character movement component in Paragon                               |
| [Seamless Travel in Lyra](https://tonetfal.github.io/posts/2023/09/Lyra%20Seamless%20Travel/)                                                                  | Fixing seamless travel problems with Modular Gameplay in Lyra         |
| [Local multiplayer](https://unrealcommunity.wiki/local-multiplayer-tips-993f4t24)                                                                              | Creating local multiplayer games                                      |
| [Dormancy](https://dev.epicgames.com/documentation/en-us/unreal-engine/actor-network-dormancy-in-unreal-engine)                                                | Save bandwidth on actors that aren't interacted with                  |
| [Dormancy example](https://www.youtube.com/watch?v=18LbGKf6QQw&feature=youtu.be)                                                                               | ^                                                                     |
| [Net Cull and relevancy](https://forums.unrealengine.com/t/dedicated-server-net-cull-distance-and-network-relevancy-for-spawned-owned-items/)                  | Save bandwidth on actors that are too far away from client            |
| [Push model and profiling](https://www.kierannewland.co.uk/push-model-networking-unreal-engine/)                                                               | Manual way of replicating properties                                  |
| [Replication flow](https://dev.epicgames.com/documentation/en-us/unreal-engine/detailed-actor-replication-flow-in-unreal-engine)                               | A detailed description of low-level actor replication                 |
| [Replication graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/replication-graph-in-unreal-engine)                                            | Create scalable worlds with a ton of replicated actors                |
| [Replication graph example](https://www.kierannewland.co.uk/replication-graph-how-to-reduce-network-bandwidth-in-unreal/)                                      | ^                                                                     |
| [Replication graph: RTS](https://www.youtube.com/watch?v=VusAHXoHF3Y)                                                                                          | ^                                                                     |
| [Prediction plugin](https://www.kierannewland.co.uk/using-the-network-prediction-plugin/)                                                                      | Improve responsiveness of your game                                   |
| [Networking problems](https://www.kierannewland.co.uk/the-problems-with-unreal-engines-default-networking/)                                                    | Addressing common problems in multiplayer games                       |
| [Replicating UObjects](https://jambax.co.uk/replicating-uobjects/)                                                                                             | Replicating UObjects                                                  |
| [More resources](https://cedric-neukirchen.net/docs/multiplayer-compendium/additional-resources/)                                                              | More resources                                                        |

</details>

<details>
<summary><a href="#gameplay-ability-system">Gameplay Ability System</a></summary>
<br>

| Name                                                                                       | Description                                                     |
|:-------------------------------------------------------------------------------------------|:----------------------------------------------------------------|
| [Simple GAS](https://landelare.github.io/2024/01/15/simple-gas-tutorial.html)              | Introduction to GAS                                             |
| [Tranek Documentation](https://github.com/tranek/GASDocumentation)                         | Vast majority of GAS features                                   |
| [Risk of Rain 2 Example](https://www.vitorcantao.com/post/gas-gameplay-framework/)         | Crafting RPG-like systems                                       |
| [Practical GAS examples](https://epicgames.ent.box.com/s/m1egifkxv3he3u3xezb9hzbgroxyhx89) | Examples on how to use GAS for different game-specific features |

</details>

<details>
<summary><a href="#user-interface">User Interface</a></summary>
<br>

| Name                                                                                                                              | Description                                                                                                                                                      |
|:----------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [UMG & Slate Compendium](https://github.com/YawLighthouse/UMG-Slate-Compendium)                                                   | Ultimate compendium about UMG and Slate                                                                                                                          |
| [Creating widgets in C++](https://unreal-garden.com/tutorials/ui-cpp-uuserwidget/)                                                | Introduction to UMG with C++                                                                                                                                     |
| [Bind Widgets to C++](https://unreal-garden.com/tutorials/ui-bindwidget/)                                                         | Introduction to UMG with C++ and Blueprints                                                                                                                      |
| [Common UI Introduction](https://unreal-garden.com/tutorials/common-ui-intro/)                                                    | New framework wrapping UMG to simplify work with UI                                                                                                              |
| [Scale UI](https://unreal-garden.com/tutorials/ui-scale/)                                                                         | Dynamically scale UI                                                                                                                                             |
| [Ultrawide monitor support](https://unreal-garden.com/tutorials/ultrawide-ui/)                                                    | Insights from [Industries of Titan](https://store.steampowered.com/app/427940/Industries_of_Titan/) to improve quality of life for users with ultrawide monitors |
| [Widget Reflector](https://unreal-garden.com/tutorials/widget-reflector/)                                                         | Tool to debug widgets                                                                                                                                            |
| [Circle progress bar](https://www.youtube.com/watch?v=_xI-YsxKS-4)                                                                | Create modular progress circle                                                                                                                                   |
| [UI Material Lab](https://www.youtube.com/watch?v=eeedwACiTO4)                                                                    | Many practical examples of cool widgets                                                                                                                          |
| [DPI](https://sharundaar.com/unraveling-the-dpi-mysteries.html)                                                                   | Build UI that accommodates a variety of screen resolutions                                                                                                       |
| [Materials and Textures](https://dev.epicgames.com/community/learning/tutorials/PnvG/unreal-engine-materials-and-textures-for-ui) | Create materials for UI                                                                                                                                          |
| [Using UVs](https://dev.epicgames.com/community/learning/tutorials/Y4Kb/unreal-engine-using-uvs-for-tech-art-and-ui)              | Find out how to use materials UVs for UI                                                                                                                         |
| [Balatro Vortex](https://www.giovannichequi.com/work/tutorial-ue5-vortex-uv-distortion-balatro-inspired)                          | How to make the same vortex effect as [Balatro](https://store.steampowered.com/app/2379780/Balatro/)                                                             |

</details>

<details>
<summary><a href="#editor-tools">Editor Tools</a></summary>
<br>

| Name                                                                                                                                                               | Description                                    |
|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------|
| [Red Tech Art Tools](https://github.com/Ryan-DowlingSoka/RedTechArtTools/tree/main)                                                                                | Different tools for technical art              |
| [Custom "Show" entries](https://dev.epicgames.com/community/learning/tutorials/XaE8/unreal-engine-custom-visualization)                                            | Add more entries to the "Show" menu            |
| [Exec functions](https://unreal.gg-labs.com/wiki-archives/common-pitfalls/exec-functions)                                                                          | Custom console commands                        |
| [Extending gameplay debugger](https://unrealcommunity.wiki/extending-gameplay-debugger-lcudh8ot)                                                                   | Adding new gameplay debugger categories        |
| [Cheat console](https://unreal-garden.com/tutorials/cheatmanager/)                                                                                                 | Add development cheats to your game            |
| [Cheat console scripts](https://unreal-garden.com/tutorials/cheat-console-scripts/)                                                                                | Shorthand multiple cheat commands into scripts |
| [Cheat console auto-complete](https://dev.epicgames.com/community/learning/tutorials/ELje/unreal-engine-how-to-add-new-auto-complete-entries-to-the-cheat-console) | Auto-complete dynamic cheat commands           |

</details>

<details>
<summary><a href="#graphics">Graphics</a></summary>
<br>

| Name                                                                                                                           | Description                                                                  |
|:-------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------|
| [Custom Depth](https://www.tomlooman.com/the-many-uses-of-custom-depth-in-unreal-4/)                                           | How to use additional depth buffers on various objects                       |
| [Custom Stencil](https://www.tomlooman.com/unreal-engine-outline-multi-color-post-process/)                                    | Render outlines                                                              |
| [Soft Outlines](https://www.tomlooman.com/unreal-engine-soft-outline/)                                                         | Render soft outlines                                                         |
| [Overlapping Custom Depth Stencils](https://medium.com/unreal-engine-technical-blog/overlapping-custom-depth-stencils-a084aa8) | Make use of overlapping custom depth stencils                                |
| [Baking](https://dev.epicgames.com/community/learning/tutorials/KPOx/unreal-engine-light-baking-and-lightmaps-a-step-~)        | Ultimate tutorial on baking                                                  |
| [Slime material](https://80.lv/articles/guide-blob-effect-in-ue4/)                                                             | Slime material                                                               |
| [Shadow blob](https://www.fab.com/listings/13c34f9e-7754-4ae1-80ce-9b545b2dd679)                                               | Plugin to quickly integrate shadow blob for a character for platformer games |
| [Materials](https://www.youtube.com/playlist?list=PL78XDi0TS4lFlOVKsNC6LR4sCQhetKJqs)                                          | Tutorial series on materials                                                 |
| [Textures](https://simonschreibt.notion.site/Texture-Packs-418b5afc18404414b45ecb1af0e5fee8)                                   | Free database of textures                                                    |

</details>

<details>
<summary><a href="#optimization">Optimization</a></summary>
<br>

| Name                                                                                                                                | Description                                                                                     |
|:------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------|
| [Unreal Insights](https://www.youtube.com/watch?v=TygjPe9XHTw)                                                                      | Basic profiling tool                                                                            |
| [General Optimization](https://www.tomlooman.com/wp-content/uploads/2022/11/Unreal-Engine-Game-Optimization-on-a-Budget.pdf)        | Utilities to identify bottlenecks in various fields                                             |
| [Graphics profiling](https://www.youtube.com/watch?v=C3lumWdwHmA)                                                                   | How to narrow down graphical bottlenecks                                                        |
| [Render Passes](https://unrealartoptimization.github.io/book/profiling/passes/)                                                     | How to narrow down graphical bottlenecks, but in text form                                      |
| [Environment Optimization](https://www.youtube.com/watch?v=ZRaeiVAM4LI)                                                             | Optimize environments                                                                           |
| [Scalability](https://dev.epicgames.com/documentation/en-us/unreal-engine/scalability-reference-for-unreal-engine)                  | Support for different hardware                                                                  |
| [Forward Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/forward-shading-renderer-in-unreal-engine)          | Support for potato hardware                                                                     |
| [Rendering Workflow](https://zuru.tech/blog/real-time-rendering-and-unreal-engine-4)                                                | Understanding how the engine deals with rendering                                               |
| [Myths](https://www.youtube.com/watch?v=S2olUc9zcB8)                                                                                | Various Unreal Engine myths                                                                     |
| [Blueprints Performance](https://intaxwashere.github.io/blueprint-performance/)                                                     | More myths                                                                                      |
| [Animation Optimization](https://dev.epicgames.com/documentation/en-us/unreal-engine/animation-optimization-in-unreal-engine)       | How to improve animation timings                                                                |
| [CMC Optimization](https://dev.epicgames.com/community/learning/knowledge-base/mo9O/unreal-engine-character-movement-optimizations) | How to improve character movement component timings                                             |
| [Networking Optimization](https://dev.epicgames.com/documentation/en-us/unreal-engine/networking-insights-in-unreal-engine)         | Identify bottlenecks and other issues in networking                                             |
| [Various Practical Optimizations](https://tonetfal.github.io/posts/2024/12/Unreal%20Engine%205%20For%20Static%20Game%20Worlds/)     | Various techniques applied to optimize [MESS](https://store.steampowered.com/app/3330050/MESS/) |
| [User Interface Optimization](https://unreal-garden.com/tutorials/ui-performance/)                                                  | How to improve user interface timings                                                           |
| [Dependency Analyser](https://github.com/alessianigretti/DependencyAnalyser)                                                        | Measure and analyse memory bottlenecks                                                          |

</details>

<details>
<summary><a href="#audio">Audio</a></summary>
<br>

| Name                                                                                                                                                                                                 | Description                                             |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------|
| [Official Audio Course](https://dev.epicgames.com/community/learning/courses/nN0/unreal-engine-understanding-audio-mixing-and/jnv/unreal-engine-understanding-audio-mixing-and-effects-introduction) | Learn about the majority of tools you can use for audio |
| [Base Audio](https://www.youtube.com/watch?v=qFHSm8qfCBA)                                                                                                                                            | Basic audio tools                                       |
| [Meta Sounds](https://www.youtube.com/watch?v=3230-FwCts0)                                                                                                                                           | New UE5 tools for audio                                 |
| [Audio Modulation](https://www.youtube.com/watch?v=xUikseZMQk0)                                                                                                                                      | Modulate audio in runtime                               |
| [Audio Modulation 2](https://dev.epicgames.com/documentation/en-us/unreal-engine/audio-modulation-quick-start-guide?app=)                                                                            | Modulate audio in runtime                               |
| [Soundscapes](https://dev.epicgames.com/documentation/en-us/unreal-engine/soundscape-quick-start)                                                                                                    | Environment or scenario dependant audio sets            |
| [Submixes](https://docs.unrealengine.com/4.27/en-US/WorkingWithAudio/Submixes/)                                                                                                                      | Split audio in multiple outputs                         |

</details>

<details>
<summary><a href="#localization">Localization</a></summary>
<br>

| Name                                                                                                                            | Description                                                                                                     |
|:--------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------|
| [Official Localization Course](https://dev.epicgames.com/community/learning/tutorials/zwPJ/unreal-engine-localization-in-depth) | Learn about vast majority of tools to localize a game                                                           |
| [Localization Tips](https://freetimecoder.net/unreal/Adventures-In-Localization/)                                               | Localization insights for [Garden Witch Life](https://store.steampowered.com/app/1240450/Garden_Witch_Life/)    |
| [Localization Tips](https://unreal-garden.com/tutorials/industries-titan-localization/)                                         | Localization insights for [Industries of Titan](https://store.steampowered.com/app/427940/Industries_of_Titan/) |
| [Pluralizing Item Names](https://unreal-garden.com/tutorials/pluralizing-names/)                                                | How to handle irregular plurals                                                                                 |

</details>

<details>
<summary><a href="#miscellaneous">Miscellaneous</a></summary>
<br>

| Name                                                                                                                 | Description                                                          |
|:---------------------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------|
| [Ari's notes](https://flassari.notion.site/UE-Tips-Best-Practices-3ff4c3297b414a66886c969ff741c5ba)                  | Random tips                                                          |
| [General debugging](https://dev.epicgames.com/community/learning/tutorials/dXl5/advanced-debugging-in-unreal-engine) | Ways to find out what's wrong with your game                         |
| [Debugging packaged game](https://unrealcommunity.wiki/debugging-a-packaged-build-o9c2ta8f)                          | Ways to find out what's wrong with your packaged game                |
| [Unreal + Git](https://miltoncandelero.github.io/unreal-git)                                                         | Tips for Git + UE                                                    |
| [Perforce Setup](https://github.com/XistGG/Perforce-Setup)                                                           | Setup Perforce with Unreal                                           |
| [Various fundamental engine systems](https://github.com/staticJPL/Unreal-Engine-Documentation/tree/Documents)        | In depth explanation of various extremely fundamental engine systems |
| [Multithreading](https://forums.unrealengine.com/t/multithreading-and-performance-in-unreal/1216417)                 | Split your work in multiple threads. UE5Coro has some tools for that |
| [Various software](https://unreal-garden.com/tutorials/what-i-use/)                                                  | Useful software for development                                      |
| [Asset Manager](https://www.tomlooman.com/unreal-engine-asset-manager-async-loading/)                                | Manage game memory by asynchronously loading assets on demand        |
| [Turn In Place](https://github.com/Vaei/TurnInPlace)                                                                 | Turn in place logic for different game genres                        |
| [Kawaii Physics](https://github.com/pafuhana1213/KawaiiPhysics)                                                      | Custom physics nodes to create cuter animations                      |
| [Game Input Database](https://gameinputdatabase.com)                                                                 |                                                                      |
| [Game UI Database](https://www.gameuidatabase.com)                                                                   |                                                                      |

</details>

<details>
<summary><a href="#blogs">Blogs</a></summary>
<br>

| Name                                                                                                | Description              |
|:----------------------------------------------------------------------------------------------------|:-------------------------|
| [Unreal Garden](https://unreal-garden.com)                                                          | Everything               |
| [x157](https://x157.github.io)                                                                      | Programming/Lyra         |
| [WizardCell](https://wizardcell.com)                                                                | Networking               |
| [Vorixo](https://vorixo.github.io/devtricks/)                                                       | Networking               |
| [Zomg](https://zomgmoz.tv/unreal/)                                                                  | Programming              |
| [Jambax](https://jambax.co.uk)                                                                      | Programming/Networking   |
| [Kieran Netwland](https://www.kierannewland.co.uk)                                                  | Networking               |
| [Quod Soler](https://www.quodsoler.com/learn-unreal-engine/unreal-engine)                           | Programming/GAS          |
| [A Clockwork Berry](https://www.aclockworkberry.com/category/game-dev/)                             | Programming/Networking   |
| [Flassari](https://flassari.notion.site/Ari-s-Unreal-Engine-Notes-1a75e43f4014464984d4fae0617e5cef) | Programming/Optimization |
| [Landelare](https://landelare.github.io)                                                            | Programming              |
| [ikrima](https://ikrima.dev/ue4guide/)                                                              | Programming              |
| [Intax](https://intaxwashere.github.io)                                                             | Programming              |
| [Kaos](https://www.thegames.dev)                                                                    | GAS                      |
| [Tonetfal](https://tonetfal.github.io)                                                              | Programming/Optimization |
| [Vitor Cantao](https://www.vitorcantao.com)                                                         | Programming              |
| [Sharundaar](https://sharundaar.com)                                                                | UI                       |

</details>
