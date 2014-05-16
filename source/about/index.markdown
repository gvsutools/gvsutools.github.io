---
layout: page
title: "About"
date: 2014-05-15 19:38
comments: false
sharing: true
footer: true
---

GVTools is a small organization started by GVSU Computer Science major Sean Fisk with the motto "Software *for* GVSU students *by* GVSU students." GVTools has two stated goals:

* Produce useful software for GVSU students that is usable by the general student population.
* Give students participating in the organization an idea of what it is like to work with a team to build and release high-quality software.

GVTools' primary product is BetterPlanner, a tool for scheduling and registration in a similar manner to MyBanner.

History
-------

The idea of GVTools was hatched in 2011 when GVSU Computer Science major Sean Fisk got tired of logging in to GVSU's network every day. At that time, GVSU used the [Bluesocket][bs] Internet gateway system. Bluesocket forced students to manually authenticate every time they wished to use the Internet. In addition, a browser that saved open tabs would open up with all tabs being redirected to the Bluesocket login page.

These problems served as an inspiration for Bluesuckit, an automated Bluesocket login manager written in C++/[Qt][qt]. However, the year after Bluesuckit development finished, GVSU switched to [802.1X][80211x] for wireless authentication. While this was a positive change, it obsoleted Bluesuckit for the most part and the program was never released. However, development of the program showed what it takes to develop a high-quality releasable product. GVSU still uses Bluesocket for their Ethernet-based Internet access.

In the winter of 2012, Sean began dabbling with what would become BetterPlanner, a piece of software which simplifies many tasks possible with MyBanner. In particular, Sean was keen to incorporate some of the best practices learned while interning at [Atomic Object][ao], a local software development company. A command-line search client was developed which could find courses based on keywords, e.g. "Fall 2012 CIS 452".

In Winter 2013, BetterPlanner was revived. Darin Douglass and Josh Edgcombe joined the team, and together with Sean they began re-writing BetterPlanner with a graphical interface and many best practices each had learned. [Python][python] and [PySide][pyside]/[Qt][qt] were chosen for language and graphical toolkit of implementation, respectively. Viewing of schedules was completed.

Fall 2013 saw the addition of Eric Vanklompenberg to the team, with many miscellaneous bugs being resolved. New features included an improved schedule view and a Mac OS X installer.

In Winter 2014, heavy recruitment from GVSU's Computing Club began. Two members were added from this stage of recruitment, Dan Kelch and Spencer Amann. Major developments during this stage included course search, a license viewer, and a Microsoft Windows installer.

Development of BetterPlanner continues now in Summer 2014.

[bs]: http://www.adtran.com/web/page/portal/Adtran/group/4042
[qt]: http://qt-project.org/
[80211x]: http://en.wikipedia.org/wiki/IEEE_802.1X
[ao]: http://atomicobject.com/
[python]: http://python.org/
[pyside]: http://pyside.org/
