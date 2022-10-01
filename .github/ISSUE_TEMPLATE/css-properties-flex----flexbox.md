---
name: css properties flex && flexbox
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

{{short description|CSS3 web layout mode}}
{{multiple issues|
{{more citations needed|date=April 2014}}
{{technical|date=April 2014}}
{{too abstract|date=Jan 2017}}
}}
{{Infobox technology standard
| title             = Flexbox
| long_name         = CSS Flexible Box Layout
| native_name       = CSS Flexible Box Layout
| native_name_lang  = en
| image             = 
| caption           = 
| status            = [[World Wide Web Consortium#Candidate recommendation (CR)|Candidate Recommendation (CR)]]
| year_started      = {{Start date|2009|07|23|df=y}}<ref name="css-flex-history">{{Cite web|url=https://www.w3.org/standards/history/css-flexbox-1|title=CSS Flexible Box Layout Module Level 1 Publication History - W3C|website=W3C|date=n.d.|access-date=2021-04-08}}</ref>
| first_published   =
| version           = Level 1<ref name="css-flex-v1">{{Cite web|url=https://www.w3.org/TR/css-flexbox-1/|title=CSS Flexible Box Layout Module Level 1|website=W3C|publication-date=2018-11-09|access-date=2021-04-08|collaboration=CSS Working Group
|editor-first1=Tab|editor-last1=Atkins Jr.
|editor-first2=Elika J.|editor-last2=Etemad
|editor-first3=Rossen|editor-last3=Atanassov
|editor-first4=Alex|editor-last4=Mogilevsky
|editor-first5=L. David|editor-last5=Baron
|editor-first6=Neil|editor-last6=Deakin
|editor-first7=Ian|editor-last7=Hickson
|editor-first8=David|editor-last8=Hyatt
}}</ref>
| version_date      = {{Start date|2018|11|09}}<ref name="css-flex-v1" />
| preview           = Working Draft
| preview_date      = {{Start date|2021|03|25}}<ref name="flexbox-draft">{{Cite web|url=https://drafts.csswg.org/css-flexbox/|title=CSS Flexible Box Layout Module Level 1|website=CSS Working Group Editor Drafts|date=2021-03-25|access-date=2021-04-08
|editor-first1=Tab|editor-last1=Atkins Jr
|editor-first2=Elika J.|editor-last2=Etemad
|editor-first3=Rossen|editor-last3=Atanassov
|editor-first4=Alex|editor-last4=Mogilevsky
|editor-first5=L. David|editor-last5=Baron
|editor-first6=Neil|editor-last6=Deakin
|editor-first7=Ian|editor-last7=Hickson
|editor-first8=David|editor-last8=Hyatt
}}</ref>
| organization      = {{Plainlist|
* {{abbr|[[World Wide Web Consortium|W3C]]|World Wide Web Consortium}}
* [[Apple Inc.|Apple]]
* [[Google]]
* [[Microsoft]]
* [[Mozilla Corporation|Mozilla]]
* [[Opera Software]]
}}
| committee         = [[CSS Working Group]]<ref name="css-flex-v1" />
| editors           = {{Plainlist|
* Tab Atkins Jr.
* Elika J. Etemad
* Rossen Atanassov
{{Collapsible list|title=Former editors|
* Alex Mogilevsky
* L. David Baron
* Neil Deakin
* Ian Hickson
* David Hyatt
}}
}}<ref name="css-flex-v1" />
| authors           = 
| base_standards    = [[CSS]]
| related_standards = 
| abbreviation      = Flexbox
| domain            = 
| license           = 
| website           = {{URL|https://www.w3.org/TR/css-flexbox-1/}}
}}

'''CSS Flexible Box Layout''', commonly known as '''Flexbox''',<ref name="css-flex-v1" /> is a [[Cascading Style Sheets#CSS 3|CSS&nbsp;3]] web layout model.<ref name="mdn-webdocs-flexbox">{{Cite web|url=https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox|title=Basic concepts of flexbox|date=n.d.|access-date=2021-04-08|website=MDN Web Docs}}</ref> It is in the [[W3C]]'s candidate recommendation (CR) stage.<ref name="css-flex-v1" /> The flex layout allows [[Responsive web design|responsive]] elements within a container to be automatically arranged  depending on viewport (device screen) size.
{{CSS}}

== Concepts ==
Most [[Web page|web pages]] are written in a combination of [[HTML]] (Hypertext Markup Language) and [[CSS]] (Cascading Style Sheets).  In short, HTML specifies the ''content and logical structure of the page'', while the CSS specifies ''how it looks'': its colors, fonts, formatting, layout, and styling.

CSS flex-box layout is a particular way to specify the layout of HTML pages.

One of the most defining features of the flex layout is its ability to form-fit, based on its viewing environment. Flex boxes can adjust in size—either decreasing, to avoid unnecessarily monopolizing space, or increasing to make room for contents to fit within its boundaries. Moreover, the flex layout is less restrictive in terms of content flow than that of other CSS layout models, which are generally uni-directional. The flex directional flow can be specified rightwards, leftwards, upwards, or downwards. Individual items within a flex container may also be automatically rearranged to suit the available layout space.<ref name="flexbox-draft" />

== History ==
In the 2000s the intensive use of the Web by [[Mobile agent|mobile agents]] motivated "liquid layouts" and [[Responsive web design#History|responsive elements]] for the growing variety of [[Display size|screen sizes]].<ref>{{Cite web|url=https://www.ibm.com/developerworks/library/wa-cssqueries/index.html|archive-url=https://web.archive.org/web/20201013191836/https://www.ibm.com/developerworks/library/wa-cssqueries/index.html|url-status=dead|archive-date=2020-10-13|title=Use CSS media queries to create responsive websites|website=IBM Developer|publication-date=2012-10-23|access-date=2021-04-08|author-first=Jeff|author-last=Bail}}</ref> 
In the 2010s, the intensive use of popular [[JavaScript]] layout [[Software framework|frameworks]], such as [[Bootstrap (front-end framework)|Bootstrap]], inspired CSS flex-box and grid layout  specifications.<ref>{{Cite web|url=https://www.smashingmagazine.com/2011/09/css3-flexible-box-layout-explained/|title=CSS3 Flexible Box Layout: Everything I Wish I Knew When I Started|website=Smashing Magazine|date=2011-09-19|access-date=2021-04-08|author-first=Richard|author-last=Shepherd}}</ref>

CSS 3 modules included solutions akin to this, like flexbox<ref name="css-flex-v1" /> and [[CSS grid layout|grid]].<ref name="css3-grid">{{Cite web|url=https://www.w3.org/TR/css-grid-1/|title=CSS Grid Layout Module Level 1|publisher=CSS Working Group|website=W3C|publication-date=2020-12-18|access-date=2021-04-08
|editor-first1=Tab|editor-last1=Atkins Jr.
|editor-first2=Elika J.|editor-last2=Etemad
|editor-first3=Rossen|editor-last3=Atanassov
|editor-first4=Oriol|editor-last4=Brufau
|editor-first5=Alex|editor-last5=Mogilevsky
|editor-first6=Phil|editor-last6=Cupp
}}</ref>

{{As of|2020|09}}, 98.69% of installed browsers (99.29% of desktop browsers<!--"tracked desktop"--> and 100% of mobile browsers<!-- "tracked mobile"-->) support CSS Flexible Box Layout.<ref name="caniuse.com">{{cite web |title=CSS Flexible Box Layout Module |url=https://caniuse.com/flexbox |work=Can I use |accessdate=2020-09-03}}</ref>

==Terminology==
The following terms are associated with the flexbox layout model.

;Flex container
:Parent element that holds all flex items. Using the CSS display property, the container can be defined as either flex or inline-flex.
;Flex item
:Any direct child element held within the flex container is considered a flex item. Any text within the container element is wrapped in an unknown flex item.
;Axes
:Each flex box contains two axes: the main and cross axes. The '''main axis''' is the axis on which the items align with each other. The '''cross axis''' is perpendicular to the main axis.
;Flex-direction
:Establishes main axis. Possible arguments: row (default), row-reverse, column, column-reverse.
;Justify-content
:Determines how content gets placed on the main axis on the current line. Optional arguments: left, right, center, space-between, space-around.
;Align-items
:Determines the default for how flex items get placed on the cross axis on each line.
;Align-content
:Determines the default for how cross axis lines are aligned.
;Align-self
:Determines how a single item is placed along the cross axis. This overrides any defaults set by align-items.

=== Directions ===
;cross-start
;cross-end
:The '''cross-start/cross-end''' sides determine where flex lines get filled with flex items from cross-start to cross-end.
;main-start
;main-end
:The '''main-start/main-end''' sides determine where to start placing flex items within the flex container, starting from the main-start end and going to the main-end end.
;Order
:Places elements in groups and determines which order they are to be placed in within the container.
;Flex-flow
:Shorthands flex-direction and flex-wrap to place the flex content.

=== Lines ===
; Lines
:Flex items can either be placed on a singular line or on multiple lines as defined by the flex-wrap property, which controls both the direction of the cross axis and how lines stack within the container.

=== Dimensions ===
; Main size
; Cross size
:'''Main size''' and '''cross size''' are the height and width of the flex container, each dealing with the main and cross axes respectively.

== Usage ==
Designating an element as a flex element requires setting the element's CSS display property to either flex or inline-flex, as follows:
<syntaxhighlight lang="CSS">display: flex;</syntaxhighlight>

Or:
<syntaxhighlight lang="CSS">display: inline-flex;</syntaxhighlight>
By setting the display to one of the two values above, an element becomes a flex container and its children, flex items. Setting the display to flex makes the container a [[HTML element#Block elements|block-level element]], while setting the display to inline-flex makes the container an [[HTML element#Inline elements|inline-level element]].<ref name="mdn-webdocs-flexbox" />

=== Align to center ===
One of flexbox's advantages is the ability to easily align items within the container to the center of a page, both vertically and horizontally.<syntaxhighlight lang="css">
display: flex;
align-items: center;
justify-content: center;
</syntaxhighlight>

==References==
{{reflist}}
<!--- After listing your sources please cite them using inline citations and place them after the information they cite. Please see http://en.wikipedia.org/wiki/Wikipedia:REFB for instructions on how to add citations. --->

{{W3C Standards}}

[[Category:Cascading Style Sheets| ]]
[[Category:Web design]]
[[Category:World Wide Web Consortium standards]]
