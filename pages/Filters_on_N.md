<div id="mw-page-base" class="noprint">

</div>

<div id="mw-head-base" class="noprint">

</div>

<div id="content" class="mw-body" role="main">

[]{#top}
[Filters on \$\\mathbb{N}\$]{dir="auto"} {#firstHeading .firstHeading lang="en"}
========================================

<div id="bodyContent" class="mw-body-content">

<div id="siteSub">

From Cantor's Attic

</div>

<div id="contentSub">

</div>

<div id="jump-to-nav" class="mw-jump">

Jump to: [navigation](#mw-navigation), [search](#p-search)

</div>

<div id="mw-content-text" class="mw-content-ltr" lang="en" dir="ltr">

\

<div id="toc" class="toc">

<div id="toctitle">

Contents
--------

</div>

-   [[1]{.tocnumber} [Reminder on real
    numbers]{.toctext}](#Reminder_on_real_numbers)
-   [[2]{.tocnumber} [Beyond real
    numbers?]{.toctext}](#Beyond_real_numbers.3F)
    -   [[2.1]{.tocnumber} [Filters]{.toctext}](#Filters)
    -   [[2.2]{.tocnumber} [Ultrafilters]{.toctext}](#Ultrafilters)
    -   [[2.3]{.tocnumber} [Sequences of real
        numbers]{.toctext}](#Sequences_of_real_numbers)
-   [[3]{.tocnumber} [References]{.toctext}](#References)

</div>

[Reminder on real numbers]{#Reminder_on_real_numbers .mw-headline}
------------------------------------------------------------------

One of the classical constructions of real numbers is to consider Cauchy
sequences of rational numbers and an equivalence relation. If
\$\\{a\_n\\}\_n\$ and \$\\{b\_n\\}\_n\$ are Cauchy sequences, then
\$\\{a\_n\\}\_n\\sim \\{b\_n\\}\_n\$ if the sequence
\$\\{a\_n-b\_n\\}\_n\$ converges to zero. The reader may refer to their
favorite source for more about Cauchy sequences.

[Beyond real numbers?]{#Beyond_real_numbers.3F .mw-headline}
------------------------------------------------------------

It would seem interesting to be able to consider *diverging* sequences
as candidates for *infinite* numbers since, at least for monotonic
increasing sequences, they exceed all Cauchy sequences.

Let \$\\{n\\}\_n\$ and \$\\{n+\\frac{1}{n}\\}\_n\$ be two clearly
diverging sequences. They satisfy the condition that
\$\\{n-(n+\\frac{1}{n})\\}\_n\$ converges to zero.

Yet an additional requirement for these to be considered as *numbers*
would be that if \$x,y,a,b\$ stand for such sequences and \$x\\sim a\$
and \$y\\sim b\$ (for some equivalence relation) then \$x\\cdot y\\sim
a\\cdot b\$.

In the example given above, the product
\$\\{n\\cdot(n+\\frac{1}{n})\\}\_n=\\{n\^2+1\\}\_n\$ and this does will
not satisfy the condition of converging to \$\\{n\^2\\}\_n\$ thus the
Cauchy equivalence relation will not do.

The goal that is achieved with ultrafilters is to provide a concept of
sequences of real numbers *agreeing almost everywhere* providing a set
endowed with the usual operations and which extends the field of real
numbers.

### [Filters]{#Filters .mw-headline}

A filter \$\\mathcal{F}\$ on \$\\mathbb{N}\$ is a set of subsets of
\$\\mathbb{N}\$ satisfying the following conditions:

-   If \$A,B\\in \\mathcal{F}\$ then \$A\\cap B\\in\\mathcal{F}\\quad\$
    (Closed under intersection)
-   If \$A\\in \\mathcal{F}\$ and \$A\\subset B\\subset \\mathbb{N}\$
    then \$B\\in \\mathcal{F}\\quad\$ (Superset property)

**Examples**

-   \$\\{A\\subseteq \\mathbb{N}\\ |\\ i\\in A\\}\$ for some natural
    number \$i\$.
-   \$\\{A\\subseteq\\mathbb{N}\\ |\\ \\mathbb{N}\\setminus A
    \\quad\\text{ is finite}\\}\$

The second example is the cofinite filter. It contains complements of
finite sets.

A filter which contains the empty set is the powerset of
\$\\mathbb{N}\$. A filter which is not the powerset is a *proper filter*

### [Ultrafilters]{#Ultrafilters .mw-headline}

An ultrafilter on \$\\mathbb{N}\$ is a proper filter which has the extra
property that for any subset \$A\$ of \$\\mathbb{N}\$ either \$A\$ or
its complement \$\\mathbb{N}\\setminus A\$ belongs to the ultrafilter.

The first example of filter is in fact an ultrafilter. It is a
*principal* ultrafilter generated by \$i\$.

Filters and ultrafilters can be defined on other sets than
\$\\mathbb{N}\$. If they are defined on finite sets, then all
ultrafilters are principal. If a filter contains a finite set then it
contains a singleton and is therefore a principal ultrafilter. Hence a
nonprincipal ultrafilter must contain all cofinite sets.

The existence of nonprincipal ultrafilters is proven using the axiom of
choice, or one of its equivalents such as Zorn's lemma.

(For more on ultrafilters, see the excellent book by Robert Goldblatt
\[[1](#bibkey_Goldblatt1998:ultrafilter)\]).

### [Sequences of real numbers]{#Sequences_of_real_numbers .mw-headline}

Let \$\\{a\_n\\}\$ and \$\\{b\_n\\}\$ be two sequences of real numbers.
We will say that they *agree almost everywhere*, modulo a nonprincipal
ultrafilter \$\\mathcal{F}\$, if the set \$\\{k\\ |\\ a\_k=b\_k\\}\$
belongs to the ultrafilter. This determines equivalence classes on
sequences of real numbers. The set of these equivalence classes is
called the set of *hyperreals* and is denoted by \${}\^\*\\mathbb{R}\$.

Real number are included in the hyperreal by identifying them with
constant sequences.

In this setting, sequences which are diverging with respect to the
Cauchy criterion, such as \$\\{n\\}\$, can become representatives of
*infinite hyperreal numbers*. They are infinite in the sense that, in
this example, it exceeds all constant sequences, hence it is greater
than any real number.

Similarly, \$\\{1/n\\}\$ represents a positive infinitesimal. It is less
than any nonzero positive real number.

An interesting question is whether all constructions of the hypperreals
are isomorphic i.e., are there properties of the hyperreals which depend
on the choice of the nonprincipal ultrafilter? The answer depends on
whether one accepts the [continuum
hypothesis](/web/20190415131732/http://cantorsattic.info/Continuum_hypothesis "Continuum hypothesis"){.mw-redirect}.
With the CH, the answer is *no*, the construction of the hyperreals does
not depend on the ultrafilter.

[References]{#References .mw-headline}
--------------------------------------

[Main
library](/web/20190415131732/http://cantorsattic.info/Library "Library")

</div>

<div class="printfooter">

Retrieved from
"[http://cantorsattic.info/index.php?title=Filters\_on\_N&oldid=1459](http://web.archive.org/web/20190415131732/http://cantorsattic.info/index.php?title=Filters_on_N&oldid=1459)"

</div>

<div id="catlinks" class="catlinks catlinks-allhidden">

</div>

<div class="visualClear">

</div>

</div>

</div>

<div id="mw-navigation">

Navigation menu
---------------

<div id="mw-head">

<div id="p-personal" role="navigation"
aria-labelledby="p-personal-label">

### Personal tools {#p-personal-label}

-   <div id="pt-createaccount">

    </div>

    [Create
    account](/web/20190415131732/http://cantorsattic.info/index.php?title=Special:UserLogin&returnto=Filters+on+N&type=signup)
-   <div id="pt-login">

    </div>

    [Log
    in](/web/20190415131732/http://cantorsattic.info/index.php?title=Special:UserLogin&returnto=Filters+on+N "You are encouraged to log in; however, it is not mandatory [o]")

</div>

<div id="left-navigation">

<div id="p-namespaces" class="vectorTabs" role="navigation"
aria-labelledby="p-namespaces-label">

### Namespaces {#p-namespaces-label}

-   <div id="ca-nstab-main">

    </div>

    [[Page](/web/20190415131732/http://cantorsattic.info/Filters_on_N "View the content page [c]")]{}
-   <div id="ca-talk">

    </div>

    [[Discussion](/web/20190415131732/http://cantorsattic.info/Talk:Filters_on_N "Discussion about the content page [t]")]{}

</div>

<div id="p-variants" class="vectorMenu emptyPortlet" role="navigation"
aria-labelledby="p-variants-label">

### [Variants]{}[](#) {#p-variants-label}

<div class="menu">

</div>

</div>

</div>

<div id="right-navigation">

<div id="p-views" class="vectorTabs" role="navigation"
aria-labelledby="p-views-label">

### Views {#p-views-label}

-   <div id="ca-view">

    </div>

    [[Read](/web/20190415131732/http://cantorsattic.info/Filters_on_N)]{}
-   <div id="ca-viewsource">

    </div>

    [[View
    source](/web/20190415131732/http://cantorsattic.info/index.php?title=Filters_on_N&action=edit "This page is protected.
    You can view its source [e]")]{}
-   <div id="ca-history">

    </div>

    [[View
    history](/web/20190415131732/http://cantorsattic.info/index.php?title=Filters_on_N&action=history "Past revisions of this page [h]")]{}

</div>

<div id="p-cactions" class="vectorMenu emptyPortlet" role="navigation"
aria-labelledby="p-cactions-label">

### [More]{}[](#) {#p-cactions-label}

<div class="menu">

</div>

</div>

<div id="p-search" role="search">

### Search

<div id="simpleSearch">

</div>

</div>

</div>

</div>

<div id="mw-panel">

<div id="p-logo" role="banner">

[](/web/20190415131732/http://cantorsattic.info/Cantor%27s_Attic "Visit the main page")

</div>

<div id="p-Directory" class="portal" role="navigation"
aria-labelledby="p-Directory-label">

### Directory {#p-Directory-label}

<div class="body">

-   <div id="n-Upper-attic">

    </div>

    [Upper
    attic](/web/20190415131732/http://cantorsattic.info/Upper_attic)
-   <div id="n-Middle-attic">

    </div>

    [Middle
    attic](/web/20190415131732/http://cantorsattic.info/Middle_attic)
-   <div id="n-Lower-attic">

    </div>

    [Lower
    attic](/web/20190415131732/http://cantorsattic.info/Lower_attic)
-   <div id="n-">

    </div>

    [](INVALID-TITLE)
-   <div id="n-The-parlour">

    </div>

    [The parlour](/web/20190415131732/http://cantorsattic.info/Parlour)

</div>

</div>

<div id="p-Resources" class="portal" role="navigation"
aria-labelledby="p-Resources-label">

### Resources {#p-Resources-label}

<div class="body">

-   <div id="n-The-playroom">

    </div>

    [The
    playroom](/web/20190415131732/http://cantorsattic.info/Playroom)
-   <div id="n-The-library">

    </div>

    [The library](/web/20190415131732/http://cantorsattic.info/Library)
-   <div id="n-The-cellar">

    </div>

    [The cellar](/web/20190415131732/http://cantorsattic.info/Cellar)

</div>

</div>

<div id="p-Community" class="portal" role="navigation"
aria-labelledby="p-Community-label">

### Community {#p-Community-label}

<div class="body">

-   <div id="n-portal">

    </div>

    [Community
    portal](/web/20190415131732/http://cantorsattic.info/Cantor%27s_Attic:Community_portal "About the project, what you can do, where to find things")
-   <div id="n-currentevents">

    </div>

    [Current
    events](/web/20190415131732/http://cantorsattic.info/Cantor%27s_Attic:Current_events "Find background information on current events")
-   <div id="n-recentchanges">

    </div>

    [Recent
    changes](/web/20190415131732/http://cantorsattic.info/Special:RecentChanges "A list of recent changes in the wiki [r]")
-   <div id="n-randompage">

    </div>

    [Random
    page](/web/20190415131732/http://cantorsattic.info/Special:Random "Load a random page [x]")
-   <div id="n-help">

    </div>

    [Help](http://web.archive.org/web/20190415131732/https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents "The place to find out")

</div>

</div>

<div id="p-tb" class="portal" role="navigation"
aria-labelledby="p-tb-label">

### Tools {#p-tb-label}

<div class="body">

-   <div id="t-whatlinkshere">

    </div>

    [What links
    here](/web/20190415131732/http://cantorsattic.info/Special:WhatLinksHere/Filters_on_N "A list of all wiki pages that link here [j]")
-   <div id="t-recentchangeslinked">

    </div>

    [Related
    changes](/web/20190415131732/http://cantorsattic.info/Special:RecentChangesLinked/Filters_on_N "Recent changes in pages linked from this page [k]")
-   <div id="t-specialpages">

    </div>

    [Special
    pages](/web/20190415131732/http://cantorsattic.info/Special:SpecialPages "A list of all special pages [q]")
-   <div id="t-print">

    </div>

    [Printable
    version](/web/20190415131732/http://cantorsattic.info/index.php?title=Filters_on_N&printable=yes "Printable version of this page [p]")
-   <div id="t-permalink">

    </div>

    [Permanent
    link](/web/20190415131732/http://cantorsattic.info/index.php?title=Filters_on_N&oldid=1459 "Permanent link to this revision of the page")
-   <div id="t-info">

    </div>

    [Page
    information](/web/20190415131732/http://cantorsattic.info/index.php?title=Filters_on_N&action=info)

</div>

</div>

</div>

</div>

<div id="footer" role="contentinfo">

-   <div id="footer-info-lastmod">

    </div>

    This page was last modified on 11 September 2017, at 12:12.
-   <div id="footer-info-viewcount">

    </div>

    This page has been accessed 15,760 times.

<!-- -->

-   <div id="footer-places-privacy">

    </div>

    [Privacy
    policy](/web/20190415131732/http://cantorsattic.info/Cantor%27s_Attic:Privacy_policy "Cantor's Attic:Privacy policy")
-   <div id="footer-places-about">

    </div>

    [About Cantor's
    Attic](/web/20190415131732/http://cantorsattic.info/Cantor%27s_Attic:About "Cantor's Attic:About")
-   <div id="footer-places-disclaimer">

    </div>

    [Disclaimers](/web/20190415131732/http://cantorsattic.info/Cantor%27s_Attic:General_disclaimer "Cantor's Attic:General disclaimer")

<!-- -->

-   <div id="footer-poweredbyico">

    </div>

    [![Powered by
    MediaWiki](/web/20190415131732im_/http://cantorsattic.info/resources/assets/poweredby_mediawiki_88x31.png){width="88"
    height="31"}](//web.archive.org/web/20190415131732/http://www.mediawiki.org/)

<div style="clear:both">

</div>

</div>