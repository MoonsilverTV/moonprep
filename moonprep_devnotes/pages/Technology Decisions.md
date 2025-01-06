- [[React]] as the frontend library
	- because I want to learn react
	- NOW which react wrapper / framework to use?
	  :LOGBOOK:
	  CLOCK: [2025-01-06 Mon 20:23:07]
	  CLOCK: [2025-01-06 Mon 20:23:09]
	  :END:
		- options:
			- Reagent (library)
				- seems closest to react
				- is a plain wrapper, needs added architecture choices
			- Re-Frame (frontend framework)
				- uses effects system for events
				- contains everything for the frontend story
				- likely i'd make many of the same architecture choices
				- not sure if i learn enough about react proper if i use this though
			- Fulcro (framework)
				- has data exchange built in
				- would be first time working with a graph api
- [[ClojureScript]] and [[Clojure]] as the main programming language
	- because I want to learn Clojure
- Open Questions:
	- LATER deliver as webserver or standalone desktop application (such as Electron)?
		- webserver has the advantage that users can use it remotely without requiring a sync engine, might even be able to make it usable on a phone
		- webserver is harder for people to set up
	- NOW How is data stored?
	  :LOGBOOK:
	  CLOCK: [2025-01-06 Mon 19:49:19]
	  :END:
		- files?
		- relational database?
		- NoSQL database?
		- LATER How is the datastore connected to the backend? (ORM and such)
	- NOW How is data transferred between frontend and backend?
	  :LOGBOOK:
	  CLOCK: [2025-01-06 Mon 19:51:56]
	  :END:
	- NOW Do i need a Router?
	  :LOGBOOK:
	  CLOCK: [2025-01-06 Mon 19:52:13]
	  :END:
		- need to think more about the application design. If there's multiple windows, then URLs make less sense
			- do routers still have benefits in this case? benefits include things like:
				- open in new tab
				- browser back button
				- page refresh
				- desktop to mobile handover
				- browser bookmarks