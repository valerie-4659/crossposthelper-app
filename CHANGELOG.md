# What's new

## v0.3.60 - 2026-08-11

- Updates: Read the feed from the hub's releases, and show what is in it


## v0.3.59 - 2026-08-11

- Updates: Keep the manual check reachable, and say when it last ran
- Tell the user when itch.io has a newer build


## v0.3.58 - 2026-08-11

- Interface: Let the AI Post batch rail scroll when it is stacked, not just beside
- Interface: Give the AI Post batch column room for a usable thumbnail
- AI posts: The spice level colours the pad, and Explicit is red
- AI posts: Spell out what the settings will produce, not just name them
- AI posts: Say what the settings add up to, and size the pad to its panel
- Interface: Mood hint and the way out of Auto go under the pad


## v0.3.57 - 2026-08-11

- Interface: The mood pad no longer owns the dialog
- Scanning: Rescan only what changed, not the whole library


## v0.3.56 - 2026-08-09

- Interface: Give the mood pad a temperature, and stop clipping its labels
- Interface: Let the mood marker actually move
- Interface: Mood as a pad you drag, not a thirteen-item dropdown
- AI posts: A source slider instead of the Context/Refine switch
- AI posts: A seductive mood, distinct from teasing
- AI posts: Moods for images that are not intimate


## v0.3.54 - 2026-08-07

- Visible zoom controls, header layout, and a way out of "not found"


## v0.3.52 - 2026-08-07

- AI posts: A perspective for when the picture is of you


## v0.3.51 - 2026-08-07

- Show how many images are selected
- Stop the image growing past the window, and add zoom
- Two cards on a dark stage, and a click that does not fight the drag
- Repair the drag icon, which broke dragging everywhere
- Picker: Put Alt on every shortcut, and drop the destructive one
- Load the shared model table from JSON, not a .cjs
- Picker: Keyboard-driven loop, and say why a button is off
- Fill the window, and zoom into the detail
- Make the full view a place you can work from
- Match a library path on Windows, and make the picker preview draggable


## v0.3.49 - 2026-08-07

- Queue: One job list with the source marked, and a working Send to Plugin
- Keep job listeners alive, and save results next to their source


## v0.3.48 - 2026-08-07

- Drop the stock menu bar on Windows and Linux
- Rotating backups with a restore that cannot corrupt anything
- Do not silently discard a whole backfill run
- Recover from a lock directory left by a killed process


## v0.3.47 - 2026-08-07

- Always free statements on the IPC query path
- Stop two instances sharing one database, and wait for locks


## v0.3.46 - 2026-08-07

- Keep the Bloom 2 seed under its ceiling, and show background work


## v0.3.45 - 2026-08-07

- Load the secondary pages on demand
- Library: Apply rating and people filters, and unstack the header
- Add Bloom 2, from one model table instead of four


## v0.3.44 - 2026-08-07

- Library: Apply rating and people filters, and unstack the header
- Add Bloom 2, from one model table instead of four


## v0.3.43 - 2026-08-07

- Library: Apply rating and people filters, and unstack the header
- Add Bloom 2, from one model table instead of four


## v0.3.42 - 2026-08-07

- Picker: Act on the image that is actually on screen
- Tag chips and picker tag/colour filter, with an empty-filter guard
- Interface: Give the sidebar room, and show what a mood actually means
- Interface: Fold the setup away, and edit tags as chips
- AI posts: Three tag tiers - always, context, maybe
- Picker: Restrict random picks by tag and colour
- AI posts: Split mood out of the content level
- AI posts: Drop repetition penalties on Grok
- Interface: Panel presets and one-click voice samples
- AI posts: Creativity setting and level-gate editing
- AI posts: Generate several drafts and pick one
- AI posts: Break the sameness between generations
- AI posts: Voice samples on personas
- AI posts: Tag priority tiers
- AI posts: Spice control and a visible image reading


## v0.3.41 - 2026-08-06

- Add a grid-sized variant
- Interface: Settings tabs, a working light mode, accessible controls
- Library: Result totals, endless scrolling, and undo for removals
- AI posts: Move ONNX sessions into a worker thread
- Library: Keyboard shortcuts for the actions used most
- Do bulk selection work in one transaction, and guard the upgrade
- Replace sql.js with an on-disk SQLite engine
- Library: Cut grid re-renders, query payload and reload storms
- Cache similarity-group results in the main process


## v0.3.40 - 2026-08-06

- Library: Setup checklist, similarity groups, and editable tags
- Copy selected library images into a reference folder


## v0.3.39 - 2026-08-06

- EP crash guard + separate manual library/reference analysis runs


## v0.3.38 - 2026-08-06

- Opt-in Reference Images library with folder tree and curation tools
- Library: Combine search terms with commas (AND)
- Library: Keep the filter bar fixed above the scrollable grid
- Library: Show search results instead of folder cards at any level
- Library: Local image intelligence — search, tags, colors, semantic search, duplicates


## v0.3.35 - 2026-08-04

- Video: Add MiniMax H3 model with reference-to-video support


## v0.3.32 - 2026-07-28

- Show actual result + post the recreated image, not source


## v0.3.31 - 2026-07-28

- Correct Bloom "Standard" model + add before/after compare


## v0.3.30 - 2026-07-20

- Surface unclaimed sends and let visible tabs win multi-tab races


## v0.3.29 - 2026-07-19

- Scheduled-send opt-out + fix silent auto-send failures


## v0.3.28 - 2026-07-19

- Scheduled-send opt-out + fix silent auto-send failures


## v0.3.27 - 2026-07-18

- Harden extension↔app connection against lost triggers and dead streams


## v0.3.26 - 2026-07-17

- Char names in placeholders, conditional hair suppression, no-cloth-colors toggle


## v0.3.25 - 2026-07-17

- Complete image thumbnails + smarter Stats model-name parsing


## v0.3.24 - 2026-07-14

- Add per-checkpoint image library and top 10 to Stats page


## v0.3.23 - 2026-07-14

- Keep AI-generated tags strictly within the approved network list
- Add zoom/pan to picker image preview for artifact inspection
- Show alternatives grid with click-to-view PNG metadata in picker


## v0.3.22 - 2026-07-11

- Checkpoint stats page, PNG metadata panel, copy-to-clipboard in lightbox
- Add per-source thumbnail rebuild button


## v0.3.21 - 2026-07-06

- Force thumbnail regeneration during full scan


## v0.3.20 - 2026-07-05

- Watcher thumbnail cache bust and longer debounce


## v0.3.19 - 2026-07-05

- Bridge trigger reliability and picker header layout


## v0.3.17 - 2026-07-04

- Add file watcher for automatic library updates


## v0.3.15 - 2026-07-02

- Enforce emoji rule in story posts when persona has style notes


## v0.3.14 - 2026-07-02

- Use CDP Input.insertText for X text injection to properly update Lexical state


## v0.3.13 - 2026-07-02

- Use CDP userGesture fill as reliable text injection for X compose


## v0.3.11 - 2026-07-02

- Ensure text is posted and only one X tab handles auto-inject


## v0.3.10 - 2026-07-02

- Add persona personality rules guide to settings UI
- Enforce persona voice + emojis in morning/goodnight/engagement posts
- Auto-inject + optional auto-post for X via Chrome extension


## v0.3.9 - 2026-07-01

- Style_notes are sole authority on emoji when persona is active


## v0.3.7 - 2026-07-01

- Personality enforcement, video results redesign, Topaz empty state


## v0.3.5 - 2026-06-30

- Replace run-all-migrations-every-start with tracked migrations


## v0.3.4 - 2026-06-30

- Download button in video queue panel for completed jobs


## v0.3.3 - 2026-06-30

- Picker folder selector, video toggle, and video preview
- Image card action strip overflow + always-visible network indicators
- Job queue download, AI instructions, and library navigation
- Multi-pick fair shuffle, stem sibling lookup, round refresh, notifications


## v0.3.2 - 2026-06-30

- Fair-shuffle picker and stable image identity via stem_id


## v0.3.1 - 2026-06-29

- Sequential Wavespeed job queue with drag-and-drop reordering


## v0.2.134 - 2026-06-29

- React to bridge:images-posted IPC event so Library updates after extension marks posts
- Merge Image/Video queues, Library UX improvements, Electron dev mode


## v0.2.133 - 2026-06-26

- Autocomplete fix


## v0.2.131 - 2026-06-26

- Bluesky direct post via AT Protocol + Library prev/next folder nav


## v0.2.130 - 2026-06-26

- Windows drag & drop + button order in AI Post panel


## v0.2.129 - 2026-06-25

- CivitAI direct post via MCP API (no browser extension needed)


## v0.2.128 - 2026-06-25

- CivitAI direct post via MCP API (no browser extension needed)


## v0.2.127 - 2026-06-19

- Better context mode


## v0.2.126 - 2026-06-16

- AI Persona handling


## v0.2.122 - 2026-06-11

- ImageGeneratePanel — gate imagePath on useRefImage toggle


## v0.2.121 - 2026-06-11

- Resolve 'images field required' error on image recreation


## v0.2.118 - 2026-06-10

- Overhaul video generation — 8 WaveSpeed models, per-model params, camera-moves checkbox, image queue bridge fix


## v0.2.115 - 2026-06-09

- Full param UI — Standard/Realism/Wonder3, creativity, enhancement, scale, outputs, preserve faces, AI prompt


## v0.2.114 - 2026-06-09

- Full param UI — Standard/Realism/Wonder3, creativity, enhancement, scale, outputs, preserve faces, AI prompt


## v0.2.113 - 2026-06-09

- AI posts: Add 'Send text to Plugin' button for queue-panel mode


## v0.2.111 - 2026-06-09

- AI posts: Add AI post generator to Image and Video Queue panels


## v0.2.110 - 2026-06-09

- Fix native file drag-out in ImageCard, ImagePreview and ImageLightbox
- Add result thumbnail preview and Reveal button
- Library and Picker modals are now fire-and-forget


## v0.2.108 - 2026-06-09

- Configurable output folder in Settings
- Background upscale jobs in Image Queue


## v0.2.106 - 2026-06-09

- Integrate detailed Image Prompt Safety Rules into sfwBlock and userPrompt


## v0.2.105 - 2026-06-09

- Use download_url field from API response — Topaz returns download_url not url
- Upscale with Topaz button on completed jobs


## v0.2.104 - 2026-06-09

- Replace inline if-statements in @click.self with guard methods — Vue template compiler rejects if as an expression
- Resolve TS2339 errors in ImageQueuePanel and VideoQueuePanel
- Remove inner double-quotes from :placeholder to fix TS1005 parse error
- New Job modal for txt2img generation with AI prompt enhancement
- Integrate Topaz Labs Image API for upscaling in Library, Picker, and Lightbox
- Download generated images, make-video from image queue, image drop on video queue
- AI analyse button in re-run modal — regenerate prompt for currently selected model


## v0.2.103 - 2026-06-09

- Remove inner double-quotes from :placeholder to fix TS1005 parse error
- New Job modal for txt2img generation with AI prompt enhancement
- Integrate Topaz Labs Image API for upscaling in Library, Picker, and Lightbox
- Download generated images, make-video from image queue, image drop on video queue
- AI analyse button in re-run modal — regenerate prompt for currently selected model


## v0.2.102 - 2026-06-09

- New Job modal for txt2img generation with AI prompt enhancement
- Integrate Topaz Labs Image API for upscaling in Library, Picker, and Lightbox
- Download generated images, make-video from image queue, image drop on video queue
- AI analyse button in re-run modal — regenerate prompt for currently selected model


## v0.2.101 - 2026-06-09

- New Job modal for txt2img generation with AI prompt enhancement
- Integrate Topaz Labs Image API for upscaling in Library, Picker, and Lightbox
- Download generated images, make-video from image queue, image drop on video queue
- AI analyse button in re-run modal — regenerate prompt for currently selected model


## v0.2.100 - 2026-06-09

- Download generated images, make-video from image queue, image drop on video queue
- AI analyse button in re-run modal — regenerate prompt for currently selected model


## v0.2.99 - 2026-06-09

- Model-specific API params — aspect/resolution for GPT+NanaBanana, size for others, quality/format/strength only where supported


## v0.2.98 - 2026-06-09

- Use async ipcRenderer.send for startDrag — sendSync blocked renderer and broke macOS drag transfer
- Sync to real Wavespeed model list — correct slugs, badges, Seedream support, ultraStrict per provider
- Edit & Re-run modal + ultra-strict SFW rewrite for GPT Image 2 / Nano Banana
- Aspect ratio auto-detect, ref-image toggle, resolution/quality/format, SFW model-specific prompting


## v0.2.96 - 2026-06-08

- Wavespeed image generation pipeline — ImageGeneratePanel, ImageQueuePanel, ImageQueuePage, 🖼 card button, Library modal, Picker sidebar section, dual-queue background poller


## v0.2.95 - 2026-06-08

- Move to dedicated nav page — remove misplaced modal buttons from Library/Picker sidebar


## v0.2.94 - 2026-06-08

- Persistent Wavespeed job queue — DB storage, background poller in main, VideoQueuePanel with live updates


## v0.2.93 - 2026-06-08

- Settings: Use named method for Wavespeed dashboard link to avoid template window scope error
- Direct image-to-video submission — API key in Settings, Send to Wavespeed in VideoPromptPanel with polling


## v0.2.92 - 2026-06-08

- Direct image-to-video submission — API key in Settings, Send to Wavespeed in VideoPromptPanel with polling


## v0.2.91 - 2026-06-08

- Direct image-to-video submission — API key in Settings, Send to Wavespeed in VideoPromptPanel with polling


## v0.2.90 - 2026-06-07

- Update
- Native OS file drag — sendSync timing fix, img draggable=false; feat(video-prompt): Reveal in Finder button


## v0.2.89 - 2026-06-05

- Picker: Add Video Prompt Generator panel — reuses VideoPromptPanel component


## v0.2.88 - 2026-06-05

- Library: Move folder preview pin to image overlay (bottom-right), remove from action row


## v0.2.86 - 2026-06-04

- Move OC blur handler to script to avoid template scope error
- Use window.setTimeout in blur handler for OC dropdown
- OC multi-select with chip UI and localStorage autocomplete


## v0.2.85 - 2026-06-04

- Move OC blur handler to script to avoid template scope error
- Use window.setTimeout in blur handler for OC dropdown
- OC multi-select with chip UI and localStorage autocomplete


## v0.2.84 - 2026-06-04

- Use window.setTimeout in blur handler for OC dropdown
- OC multi-select with chip UI and localStorage autocomplete


## v0.2.83 - 2026-06-04

- OC multi-select with chip UI and localStorage autocomplete


## v0.2.81 - 2026-06-03

- Adding video prompt generation


## v0.2.80 - 2026-06-03

- Picker: Compact sidebar UI, remove description text


## v0.2.79 - 2026-06-03

- Add aiInstructions param to desktop.d.ts generatePost signature
- Platform switcher, AI instructions, compact UI, prompt overhaul


## v0.2.78 - 2026-06-03

- Platform switcher, AI instructions, compact UI, prompt overhaul


## v0.2.77 - 2026-06-03

- Platform switcher, AI instructions, compact UI, prompt overhaul


## v0.2.75 - 2026-06-02

- Library: Add Send to Plugin + AI Post buttons to collection panel
- Use document.createElement override for instance-level click suppression


## v0.2.74 - 2026-06-02

- Remove userGesture:true to prevent OS file picker from opening


## v0.2.72 - 2026-06-02

- Add userGesture:true + triple-interceptor for file input capture


## v0.2.70 - 2026-06-02

- Switch to CDP injection to bypass isolated-world limitation


## v0.2.69 - 2026-06-02

- Rewrite adapter for current bsky.app DOM structure


## v0.2.68 - 2026-06-02

- Add global archive/restore button + misc fixes
- Use CDP injection for react-dropzone compatibility


## v0.2.67 - 2026-06-01

- Library: Propagate mark-as-posted to filename-stem siblings


## v0.2.66 - 2026-06-01

- Library: Propagate mark-as-posted to filename-stem siblings


## v0.2.65 - 2026-06-01

- Library: Propagate mark-as-posted to filename-stem siblings


## v0.2.64 - 2026-06-01

- Library: Propagate mark-as-posted to filename-stem siblings


## v0.2.63 - 2026-06-01

- Library: Propagate mark-as-posted to filename-stem siblings


## v0.2.62 - 2026-06-01

- Library: Image upload via button, Drag & Drop, and clipboard paste
- Picker: Restore computed import removed during cooldown refactor
- Picker: Persist skip cooldown in DB (migration 008)
- Picker: Skip cooldown (40% pool threshold) + global exclude
- AI posts: Enforce minimum 1-3 emojis in every output, especially story


## v0.2.61 - 2026-05-31

- AI posts: Match text explicitness to image content level
- AI posts: Rebuild all post-type rules with proper perspective + variety
- AI posts: Story mode writes emotional narrative, not image description
- AI posts: Replace generic star/sparkle emojis with expressive NSFW-niche ones


## v0.2.60 - 2026-05-30

- AI posts: Improve post generation quality


## v0.2.59 - 2026-05-30

- AI posts: QT Event ignores TFTT line when hint/context is set
- Add onQueueCleared/offQueueCleared to desktop.bridge type
- Library: Clear collection only after Mark as Posted, not on queue send


## v0.2.57 - 2026-05-29

- Browser extension: Stale images on second post
- Library: Close collection tray when collection is emptied


## v0.2.56 - 2026-05-29

- Prevent browser caching of queue/image GET requests


## v0.2.54 - 2026-05-29

- AI posts: Persona system message uses styleNotes directly, no conflicting emojiRule override
- AI posts: Suppress neutral-observer perspSuffix when persona is active


## v0.2.52 - 2026-05-29

- AI posts: Persona and perspective are independent; post-type rules don't override persona tone
- AI posts: Persona default perspective = first-person, not neutral observer


## v0.2.51 - 2026-05-29

- AI posts: Persona via system message — enforces voice, emoji and behavior rules
- Default max length = 180, remove auto option, clean preset labels


## v0.2.50 - 2026-05-29

- Picker: Send-mode split-button dropdown — same 3 modes as AiPostPanel


## v0.2.49 - 2026-05-29

- Send-mode dropdown + fixed 180-char default
- Rename extension buttons to clear full-width labels


## v0.2.48 - 2026-05-28

- Library: Don't close AI panel after queuing — user closes it manually
- Images only button — queues images, clears text from bridge, copies text+tags to clipboard
- Add 360/540/720 char presets for multi-image posts


## v0.2.47 - 2026-05-28

- AI posts: Send all images to AI + auto-scale text length per image count
- 180-char limit ignored + tag cursor trap in X composer


## v0.2.45 - 2026-05-28

- Move cursor to start after injection so user can edit


## v0.2.44 - 2026-05-28

- AI posts: Enforce all named characters from context must appear in post
- Library: Restore folder+selection on remount (Settings→Library)


## v0.2.43 - 2026-05-28

- AI posts: Context hint is now mandatory and first rule in prompt
- Settings: Toggle knob overflow + correct ON translate offset


## v0.2.42 - 2026-05-28

- Show Max length dropdown for ALL X posts, not just Premium+
- Library: Persist selected images + collection across navigation/restart


## v0.2.41 - 2026-05-28

- Toggle alignment + library state persistence


## v0.2.38 - 2026-05-28

- Tagged-by field → TFTT @handle line 3


## v0.2.37 - 2026-05-28

- Library: Remove header subtitle, give header breathing room (py-4)
- Settings navigation + QT event name input
- Writing personas + X Premium+ + story narratives
- Close hashtag autocomplete + finalise blue hashtag nodes after text inject


## v0.2.36 - 2026-05-28

- Curated NSFW/adult AI-art tag pool for X (migration 005)


## v0.2.35 - 2026-05-28

- Edited AI text now correctly sent to extension


## v0.2.34 - 2026-05-28

- Editable AI result, modern filter UI, per-network skip, history page


## v0.2.32 - 2026-05-26

- AI post modal in library, optional perspective, one-step queue
- Library sorting (date/name/pick), folder history, fix text injection


## v0.2.31 - 2026-05-26

- AI post modal in library, optional perspective, one-step queue
- Library sorting (date/name/pick), folder history, fix text injection


## v0.2.30 - 2026-05-26

- Shared AiPostPanel, post types, perspective, incremental scan, network hide filter, library sorting


## v0.2.29 - 2026-05-26

- Shared AiPostPanel, post types, perspective, incremental scan, network hide filter, library sorting


## v0.2.27 - 2026-05-23

- AI hint input + full-res picker preview
- Text injection duplicates + debug queue-slot diagnostics


## v0.2.26 - 2026-05-22

- Job Queue system + unified Send-to-Extension flow


## v0.2.24 - 2026-05-22

- Cross-folder collection tray, folder preview thumbnails, AI post generator, multi-network queue


## v0.2.21 - 2026-05-21

- Use convertFileSrc for multi-pick slot images (Windows path fix)


## v0.2.20 - 2026-05-21

- Multi-Pick mode in Picker — folder selection, N random slots, fill/remove, queue for extension


## v0.2.19 - 2026-05-20

- Collections — named image sets across folders, queue for any network
- DeviantArt adapter — use getQueuedImages, return imageIds[], add non-www manifest entry
- Add www.civitai.red to manifest content_scripts and popup PLATFORMS


## v0.2.18 - 2026-05-20

- X injection — click media button first to init React handler, then CDP setFileInputFiles


## v0.2.17 - 2026-05-20

- X image injection via CDP DOM.setFileInputFiles — trusted native change event
- X injection — drag-drop primary, revert native-event regression


## v0.2.16 - 2026-05-20

- X injection — use getter override + always fire native change event
- Sticky compact action toolbar in Library — no more scrolling to post
- Show per-network post counts on folder cards in Library
- Auto-scroll to last visited folder on back-navigation
- Library grid 3→6 columns responsive (3/4/5/6)


## v0.2.15 - 2026-05-20

- Show full image in library grid (natural aspect ratio, no crop)


## v0.2.13 - 2026-05-20

- X adapter — use React internal props for file injection (React 17/18 event delegation)
- Highlight last visited folder when navigating back
- Excluded folders — mark folder as done, hidden from Picker + Library by default


## v0.2.12 - 2026-05-20

- Delete images/folders, lightbox nav+select+delete, hard reset


## v0.2.11 - 2026-05-19

- Multi-image posting — app controls selection, extension injects queue


## v0.2.10 - 2026-05-19

- Use 3-slash localfile:/// URLs to preserve Windows drive letter


## v0.2.9 - 2026-05-19

- Use 3-slash localfile:/// URLs to preserve Windows drive letter


## v0.2.8 - 2026-05-19

- Replace net.fetch with fs.promises.readFile in localfile:// handler


## v0.2.7 - 2026-05-19

- Handle duplicate backslash/forwardslash rows in path migration


## v0.2.6 - 2026-05-19

- Auto-migrate backslash paths on DB open + fix thumbnail URL on Windows


## v0.2.5 - 2026-05-19

- Batch-index local folder scans in a single SQL transaction


## v0.2.4 - 2026-05-19

- Normalise path separators + fix localfile:// handler on Windows


## v0.2.3 - 2026-05-19

- Offload folder scan to Worker Thread to keep UI responsive
- Live scan progress indicator


## v0.2.2 - 2026-05-19

- Set vite base to './' for Electron file:// protocol on Windows


## v0.2.1 - 2026-05-19

- Clean dist-electron/ before build + filter artifacts by version


## v0.2.0 - 2026-05-18

- Browser extension + Firefox support + in-app download page


## v0.1.2 - 2026-05-17

- Target Windows x64 for cross-platform compatibility


## v0.1.1 - 2026-05-17

- Migrate from Tauri to Electron
- Add cross-platform release workflow
- Add about page and theme switcher
- Add bulk image posting workflow
- Make library the manual posting workflow
- Allow saving local folder sources
- Add tauri application icons
- Add hash-aware scan and import merge
- Build picker library and scan UI
- Add local image data layer
