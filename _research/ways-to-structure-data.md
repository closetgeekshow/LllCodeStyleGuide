# Different ways to structure data - #27 by boisjere - Queries

Clipped from: https://discuss.logseq.com/t/different-ways-to-structure-data/8819/27

[@Ramses](https://discuss.logseq.com/u/ramses)

-   Why is this an anti-pattern?
-   It’s an indented outline!

* * *

**HIERARCHIES NEED NOT BE STRICT**

-   As alex0 says, there need be nothing “strict” about these hierarchies.
-   Think of hierarchies as flashlight beams into your graph.
-   You can have several, illuminating your graph from different angles.
-   A block or page can turn up in several hierarchies.
-   Sometimes you want to look into your graph, and go to a specific place, and start working there.
-   It’s a wayfinding or orientation aid, exactly like Nick Milo’s MOC and Datascope concepts.

* * *

**IT’S MORE LIKE AN “OUTLINER-STYLE” MOC HUB**

-   It’s fine if most of the pages in my graph don’t show up in this MOC-type of view of namespaces.
-   I don’t intend this hierarchical “net” I’ve thrown across part of my graph to be exhaustive.
-   I’d expect the number of pages directly returned by “Hierarchies” to be small, compared to the number returned by “All Pages”.

* * *

**IT’S THE SAME OUTLINER PATTERN - AT A HIGHER LEVEL OF ORGANIZATION**

-   It’s just an way to visually review all the **pages** I’ve chosen to relate in branching patterns
-   It lets me get into my graph spatially, instead of temporally.
-   I’m a spatial/navigational thinker (not a visual thinker - I don’t need an infinite canvas and stickies!)
-   I like & want Logseq’s default view of information - outlines - but at a higher level of organization (pages in namespaces)

* * *

**SHORTCOMINGS OF MY INITIAL NAMESPACE-BASED EXAMPLE**

In the example/screencap I shared, I used a hard-coded scheme based on namespaces. That may be distracting. It may make it seem like I only wanted this for namespaces.

Technically, it’s possible hierarchies could be created more flexibly, using queries and page properties, which alex0 figured out (as I describe below).

But for my own inadequate, limited, purely namespace-based example, I ran a query something like this:

And that returned something like this:

**I WISH I COULD EDIT THAT RETURNED OUTLINE**

But I can’t edit that outline, to add headers, and text blocks to explain what’s down each branch. That would make this a true MOC hub.

More ambitiously, it would be cool to move and rename pages here, and have those structural changes cascade through my graph.

Basically, Logseq won’t let us **do to namespaced pages** what it lets us **do to blocks on pages**. (Unless we do it manually).

I just want to keep doing my “Logseq thing”, over this higher level of organization.

* * *

**IT’S ALREADY A FEATURE IN DEVELOPMENT**

-   It’s hard to see it as an anti-pattern when it’s already what gets returned by the {{namespace}} query.
-   Logseq **already** supports a very rudimentary version of the feature of aggregating and displaying namespaced pages.
-   I’m just providing input about how this **existing** feature can be enriched and expanded.

* * *

**BEING "OUTLINE-STYLE MOC-FRIENDLY IS A GOOD DIFFERENTIATOR**

-   I think there is huge potential here for Logseq to become very distinct from both Roam and Obsidian.
-   Why not support outlines above the level of the page - editable outlines of namespaced pages?
-   Right now, we can build those manually
-   But the _namespace information exists in the database_, so it _could_ be automatically generated

* * *

-   Alternatively, we could add a “type:: hierarchy” property that takes a path as a value maybe
-   Then a system-provided “Hierarchies” page could show multiple hierarchies.
-   Again, these would be like MOCs, not exhaustive TOCs of the graph
-   “Hierarchies” becomes an MOC hub, not a document root for all pages

* * *

**COMBINING NAMESPACE AND QUERY-BASED HIERARCHIES IN THE MOC HUB**

-   The hierarchy I explored was only a namespace-based one
-   That’s only because I didn’t have the knowledge on how to do it using queries over properties.
-   The queries + properties solution could be implemented if alex0’s Feature Request here was implemented: [Specify and display relations between pages/tags](https://discuss.logseq.com/t/specify-and-display-relations-between-pages-tags/9005).

* * *

-   Namepace-based hierarchies and property-based ones could conceivably all appear in the MOC-hub (the “Hierarchies” page)
-   If the information appearing there was editable (with restrictions), we could add headings into that “Hierarchies” outline to clarify what the different MOCs/hierarchies are

* * *

**NOT AN ANTI-PATTERN (NECESSARILY)**

-   tl;dr - I’M just saying that Parent-Child context matters, at a higher level than just _on_ the page.
    
-   If this higher level of outlining was forced and exhaustive, it would be an anti-pattern
    
-   Since it’s not, it’s actually just a combination of the main pattern (indented outline) and a secondary pattern (namespaces) that is already supported
    
-   People would just have to be advised, as Nick Milo does for Obsidian users, that trying to make MOCs exhaustive is a bad idea.
    
-   MOCs are accelerators, not organizers.
    
-   It’s wayfinding for people who think about their personal information topically, instead of by today’s date.
    

* * *

**SUPPORT HUMANS, NOT IDEOLOGIES**

-   Different people will differ in the amount of higher-level organization they need to avoid disorientation
-   According to the book “The Science of Managing Our Digital Stuff”, most people far prefer navigational methods to search (for personal information management tasks).
-   Using term-based methods like tagging or search is less preferred for personal info (unlike with public information like web pages)

* * *

**NAVIGATION FREES UP MENTAL RESOURCES**

-   People need navigational structures because then they can rely on recognition instead of recall to access their info, and procedural rather than declarative memory
-   This is especially important if ever Logseq wants to attract a user base that doesn’t necessarily use the tool every single day.
-   Those kinds of users would need recognition-based cues to get reoriented to their graph, and not have to dredge up declarative memories of what might be in there.
-   If the research findings about PIM hold up, the tool that achieves the best balance of navigational structure and distributed graph traversal will have a strong advantage in the marketplace

* * *

**ENJOY THE MAGIC, BUT CHOOSE YOUR STARTING POINT**

-   The magic of graph traversal is you can have serendipitous discovery of linkages that grow in value over time
-   But what is the value of doing that from an abstract, search-driven starting point every time?
-   Why not chose a topic-based starting point or launchpad, and _then_ enjoy the graph-traversal magic?
-   Logseq can become the tool that best balances both wayfinding impulses, leveraging the new graph-traversal paradigm, with just-enough-wayfinding-structure for people more familiar with older approaches

* * *

**PRAGMATISM OVER PURISM**

-   Roam is doctrinaire and purist about its graph database philosophy, and hostile to hierarchies.
-   I finally became loyal to Logseq **because** I saw the word “Hierarchies” on a page!!
-   (Also, because key evangelists were badly treated by Roam, I thought)
-   Since it’s there, I figured the Hierarchies functionality would continue to be developed.
-   It would make me sad to learn hierarchies are an anathema to the philosophy and culture of the Logseq developers.
-   That’s why I asked: [Would a rich commitment to hierarchies and classification be an anathema to Logseq culture?](https://discuss.logseq.com/t/would-a-rich-commitment-to-hierarchies-and-classification-be-an-anathema-to-logseq-culture/8327)
