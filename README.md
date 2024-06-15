<!DOCTYPE html>
<html class="client-js ve-available" lang="en" dir="ltr"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
<meta charset="UTF-8">
<title>Build lab - BetaWiki</title>
<meta name="ResourceLoaderDynamicStyles" content="">
<link rel="stylesheet" href="Build%20lab%20-%20BetaWiki_files/load_002.css">
<meta name="generator" content="MediaWiki 1.39.7">
<meta name="format-detection" content="telephone=no">
<meta property="og:site_name" content="BetaWiki">
<meta property="og:description" content="An open encyclopedia of software history">
<meta name="viewport" content="width=1000">
<link rel="alternate" type="application/x-wiki" title="Edit" href="https://betawiki.net/index.php?title=Build_lab&amp;action=edit">
<link rel="icon" href="https://betawiki.net/favicon.ico">
<link rel="search" type="application/opensearchdescription+xml" href="https://betawiki.net/opensearch_desc.php" title="BetaWiki (en)">
<link rel="EditURI" type="application/rsd+xml" href="https://betawiki.net/api.php?action=rsd">
<link rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/">
<link rel="alternate" type="application/atom+xml" title="BetaWiki Atom feed" href="https://betawiki.net/index.php?title=Special:RecentChanges&amp;feed=atom">
</head>
<body class="mediawiki ltr sitedir-ltr mw-hide-empty-elt ns-0 ns-subject mw-editable page-Build_lab rootpage-Build_lab skin-watercolor action-view"><div id="mw-page-base" class="noprint"></div>
<div id="mw-head-base" class="noprint"></div>
<div id="content" class="mw-body ve-init-mw-desktopArticleTarget-targetContainer" role="main">
	<a id="top"></a>
	<div id="siteNotice"></div>
	<div class="mw-indicators">
	</div>
	<h1 id="firstHeading" class="firstHeading mw-first-heading"><span class="mw-page-title-main">Build lab</span></h1>
	<div id="bodyContent" class="vector-body">
		<div id="siteSub" class="noprint"></div>
		<div id="contentSub"></div>
		<div id="contentSub2"></div>
		
		<div id="jump-to-nav"></div>
		<a class="mw-jump-link" href="#mw-head"></a>
		<a class="mw-jump-link" href="#searchInput"></a>
		<div id="mw-content-text" class="mw-body-content mw-content-ltr" lang="en" dir="ltr"><div class="mw-parser-output"><p>A <b>build lab</b> (or simply a <b>lab</b>) commonly refers to a <a href="https://betawiki.net/wiki/Microsoft_Windows" title="Microsoft Windows">Microsoft Windows</a> source code branch. By extension, it can also refer to the team that works on this branch.
</p><p>Historically, the build lab was a physical room populated with machines that periodically produced mainline builds of <a href="https://betawiki.net/wiki/Windows_NT" class="mw-redirect" title="Windows NT">Windows NT</a>.
 At first, there was a single build lab for the entire project that all 
developers submitted their changes to. As the number of developers grew,
 the concept of virtual build labs was introduced, where each team 
developing a subset of the feature set works on its own separate branch 
and has one or more machines compiling periodic builds of that branch. 
Each developer first submits their changes to their team's branch, and 
are merged to the mainline development branch only after meeting a 
required subset of acceptance criteria. Other teams can then pull the 
changes from the mainline branch into their development branches.
</p><p>Builds that were not built by the build lab machines, but are 
rather compiled by individual Microsoft employees, are called private 
builds. They are identified by having the <code>VS_FF_PRIVATEBUILD</code>
 file flag set in the executable's version information and by including 
the account name of the individual or service that initiated the build 
in the branch part of the build tag.<sup id="cite_ref-1" class="reference"><a href="#cite_note-1">[a]</a></sup><sup id="cite_ref-2" class="reference"><a href="#cite_note-2">[b]</a></sup>
</p>
<div id="toc" class="toc" role="navigation" aria-labelledby="mw-toc-heading"><input type="checkbox" role="button" id="toctogglecheckbox" class="toctogglecheckbox" style="display:none"><div class="toctitle" lang="en" dir="ltr"><h2 id="mw-toc-heading">Contents</h2><span class="toctogglespan"><label class="toctogglelabel" for="toctogglecheckbox"></label></span></div>
<ul>
<li class="toclevel-1 tocsection-1"><a href="#Labs"><span class="tocnumber">1</span> <span class="toctext">Labs</span></a>
<ul>
<li class="toclevel-2 tocsection-2"><a href="#Whistler_and_pre-reset_Longhorn"><span class="tocnumber">1.1</span> <span class="toctext">Whistler and pre-reset Longhorn</span></a></li>
<li class="toclevel-2 tocsection-3"><a href="#Since_Longhorn_reset"><span class="tocnumber">1.2</span> <span class="toctext">Since Longhorn reset</span></a>
<ul>
<li class="toclevel-3 tocsection-4"><a href="#Feature_branch_prefixes"><span class="tocnumber">1.2.1</span> <span class="toctext">Feature branch prefixes</span></a></li>
<li class="toclevel-3 tocsection-5"><a href="#Release_branch_prefixes"><span class="tocnumber">1.2.2</span> <span class="toctext">Release branch prefixes</span></a></li>
<li class="toclevel-3 tocsection-6"><a href="#Branch_prefixes_used_by_other_teams"><span class="tocnumber">1.2.3</span> <span class="toctext">Branch prefixes used by other teams</span></a></li>
</ul>
</li>
</ul>
</li>
<li class="toclevel-1 tocsection-7"><a href="#See_also"><span class="tocnumber">2</span> <span class="toctext">See also</span></a></li>
<li class="toclevel-1 tocsection-8"><a href="#Notes"><span class="tocnumber">3</span> <span class="toctext">Notes</span></a></li>
<li class="toclevel-1 tocsection-9"><a href="#References"><span class="tocnumber">4</span> <span class="toctext">References</span></a></li>
<li class="toclevel-1 tocsection-10"><a href="#External_links"><span class="tocnumber">5</span> <span class="toctext">External links</span></a></li>
</ul>
</div>

<h2><span class="mw-headline" id="Labs">Labs</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=1" class="mw-editsection-visualeditor" title="Edit section: Labs">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=1&amp;veaction=editsource" title="Edit section: Labs">edit source</a><span class="mw-editsection-bracket">]</span></span></h2>
<p>Microsoft has used several branching systems since the start of <a href="https://betawiki.net/wiki/Windows_XP" title="Windows XP">Windows XP</a>
 development, which differ in the hierarchy of labs as well as in the 
naming scheme. However, there are some specifics common to most schemes,
 such as the presence of a top-most main branch, or the use of special 
branches for important development milestones.
</p>
<h3><span class="mw-headline" id="Whistler_and_pre-reset_Longhorn">Whistler and pre-reset Longhorn</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=2" class="mw-editsection-visualeditor" title="Edit section: Whistler and pre-reset Longhorn">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=2&amp;veaction=editsource" title="Edit section: Whistler and pre-reset Longhorn">edit source</a><span class="mw-editsection-bracket">]</span></span></h3>
<p>The top-most branch was called <b>main</b>, which integrated changes 
from all labs. Under it were several numbered labs, each of which was 
working on a separate part of Windows, such as:
</p>
<ul><li><b>Lab01</b>: Kernel</li>
<li><b>Lab02</b>: Networking</li>
<li><b>Lab03</b>: Server<sup id="cite_ref-3" class="reference"><a href="#cite_note-3">[c]</a></sup></li>
<li><b>Lab04</b>: Terminal Services<sup id="cite_ref-4" class="reference"><a href="#cite_note-4">[1]</a></sup></li>
<li><b>Lab06</b>: User interface</li>
<li><b>Lab07</b>: Internet Information Services/COM+</li></ul>
<p>These labs also had a "_N" branch, which served as a buffer between 
main and the actual branch. For example, changes from the main branch 
would first get integrated into Lab06_N before later being integrated 
into Lab06 in a process called forward integration. The same applied for
 reverse integration, where the lab would first integrate changes into 
its N-branch before integrating them into the main branch.
</p><p>There were also <b>idx</b> (internal development 
workstation/server) branches, builds from which are usually 
recompilations intended for TAP/OEM partners. However, they were also 
occasionally released for public testing, e.g. <a href="https://betawiki.net/wiki/Windows_Longhorn_build_4074" title="Windows Longhorn build 4074">Windows Longhorn build 4074</a> or <a href="https://betawiki.net/wiki/Windows_XP_build_2257" title="Windows XP build 2257">Windows XP build 2257</a>.
</p><p>Before the release of <a href="https://betawiki.net/wiki/Windows_XP" title="Windows XP">Windows XP</a>, the main branch was forked into the <b>xpclient</b> branch while the main branch moved on to track <a href="https://betawiki.net/wiki/Windows_Server_2003" title="Windows Server 2003">Windows Server 2003</a>
 development. After the final version was shipped, new branches were 
created for updates, hotfixes and Service Pack development. Similarly, 
the <b>dnsrv</b> branch (short for Dot NET Server, i.e. Windows .NET 
Server) was forked from the main branch before the release of Windows 
Server 2003.
</p>
<h3><span class="mw-headline" id="Since_Longhorn_reset">Since Longhorn reset</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=3" class="mw-editsection-visualeditor" title="Edit section: Since Longhorn reset">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=3&amp;veaction=editsource" title="Edit section: Since Longhorn reset">edit source</a><span class="mw-editsection-bracket">]</span></span></h3>
<p>The lab hierarchy was overhauled after the development reset of <a href="https://betawiki.net/wiki/Windows_Vista" title="Windows Vista">Longhorn</a>
 to address the flaws that plagued most of the pre-reset period. Instead
 of having a small amount of general virtual build labs each focusing on
 a different general scope of Windows functionality, a new hierarchial 
model with considerably more feature branches was introduced, which 
helped reduce the amount of code to reverse integrate for branch. 
Microsoft also set stricter criteria for reverse integrating changes 
from the labs into the main branch, which was now renamed to <b>winmain</b>.
</p><p>The main branch was later renamed to <b>rsmain</b> at some point after the release of <a href="https://betawiki.net/wiki/Windows_10" title="Windows 10">Windows 10</a>, and then to <b>rsmaster</b>
 after the Windows source repository's conversion to Git, likely to 
comply with the Git convention of calling the top-most branch the <code>master</code> branch. At some point after February 2021,<sup id="cite_ref-5" class="reference"><a href="#cite_note-5">[2]</a></sup> the branch was renamed back to <b>main</b>.
 This was likely done in order to follow suit with other Microsoft 
projects after the master/slave terminology became a subject of 
controversy in 2020 due to <a href="https://en.wikipedia.org/wiki/slavery" class="extiw" title="w:slavery">slavery</a> connotations.<sup id="cite_ref-6" class="reference"><a href="#cite_note-6">[3]</a></sup><sup id="cite_ref-7" class="reference"><a href="#cite_note-7">[4]</a></sup>
</p>
<h4><span class="mw-headline" id="Feature_branch_prefixes">Feature branch prefixes</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=4" class="mw-editsection-visualeditor" title="Edit section: Feature branch prefixes">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=4&amp;veaction=editsource" title="Edit section: Feature branch prefixes">edit source</a><span class="mw-editsection-bracket">]</span></span></h4>
<p>Microsoft has used multiple prefixes to refer to feature branches over time:  
</p>
<ul><li><b>vbl</b> (virtual build lab) � <a href="https://betawiki.net/wiki/Windows_Vista" title="Windows Vista">Windows Vista</a></li>
<li><b>fbl</b> (feature branch level) � <a href="https://betawiki.net/wiki/Windows_7" title="Windows 7">Windows 7</a> up to <a href="https://betawiki.net/wiki/Windows_10_(original_release)" title="Windows 10 (original release)">Windows 10 (original release)</a></li>
<li><b>rs</b> (Redstone) � <a href="https://betawiki.net/wiki/Windows_10_Creators_Update" title="Windows 10 Creators Update">Windows 10 Creators Update</a> up to now</li>
<li><b>fs</b> (Firesteel) � <a href="https://betawiki.net/wiki/Windows_11_(original_release)" title="Windows 11 (original release)">Windows 11 (original release)</a><sup id="cite_ref-8" class="reference"><a href="#cite_note-8">[d]</a></sup></li></ul>
<p><a href="https://betawiki.net/wiki/Windows_10_November_Update" title="Windows 10 November Update">Windows 10 November Update</a> and <a href="https://betawiki.net/wiki/Windows_10_Anniversary_Update" title="Windows 10 Anniversary Update">Windows 10 Anniversary Update</a> used their respective release branch prefix for feature branches � <b>th2</b> and <b>rs1</b>, respectively.
</p>
<h4><span class="mw-headline" id="Release_branch_prefixes">Release branch prefixes</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=5" class="mw-editsection-visualeditor" title="Edit section: Release branch prefixes">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=5&amp;veaction=editsource" title="Edit section: Release branch prefixes">edit source</a><span class="mw-editsection-bracket">]</span></span></h4>
<p>Similarly to the previous system, the main branch is forked off 
before release to contain update development. The following is the list 
of known prefixes: 
</p>
<ul><li><b>vista</b>, <b>longhorn</b>, <b>lh</b> � <a href="https://betawiki.net/wiki/Windows_Vista" title="Windows Vista">Windows Vista</a>, <a href="https://betawiki.net/wiki/Windows_Server_2008" title="Windows Server 2008">Windows Server 2008</a></li>
<li><b>win7</b> � <a href="https://betawiki.net/wiki/Windows_7" title="Windows 7">Windows 7</a>, <a href="https://betawiki.net/wiki/Windows_Server_2008_R2" title="Windows Server 2008 R2">Windows Server 2008 R2</a></li>
<li><b>win8</b> � <a href="https://betawiki.net/wiki/Windows_8" title="Windows 8">Windows 8</a>, <a href="https://betawiki.net/wiki/Windows_Server_2012" title="Windows Server 2012">Windows Server 2012</a></li>
<li><b>winblue</b> � <a href="https://betawiki.net/wiki/Windows_8.1" title="Windows 8.1">Windows 8.1</a>, <a href="https://betawiki.net/wiki/Windows_Server_2012_R2" title="Windows Server 2012 R2">Windows Server 2012 R2</a></li>
<li><b>th1</b> � <a href="https://betawiki.net/wiki/Windows_10_(original_release)" title="Windows 10 (original release)">Windows 10 (original release)</a></li>
<li><b>th2</b> � <a href="https://betawiki.net/wiki/Windows_10_November_Update" title="Windows 10 November Update">Windows 10 November Update</a></li>
<li><b>rs1</b> � <a href="https://betawiki.net/wiki/Windows_10_Anniversary_Update" title="Windows 10 Anniversary Update">Windows 10 Anniversary Update</a>, <a href="https://betawiki.net/wiki/Windows_Server_2016" title="Windows Server 2016">Windows Server 2016</a></li>
<li><b>rs2</b> � <a href="https://betawiki.net/wiki/Windows_10_Creators_Update" title="Windows 10 Creators Update">Windows 10 Creators Update</a></li>
<li><b>rs3</b> � <a href="https://betawiki.net/wiki/Windows_10_Fall_Creators_Update" title="Windows 10 Fall Creators Update">Windows 10 Fall Creators Update</a></li>
<li><b>rs4</b> � <a href="https://betawiki.net/wiki/Windows_10_April_2018_Update" title="Windows 10 April 2018 Update">Windows 10 April 2018 Update</a></li>
<li><b>rs5</b> � <a href="https://betawiki.net/wiki/Windows_10_October_2018_Update" title="Windows 10 October 2018 Update">Windows 10 October 2018 Update</a>, <a href="https://betawiki.net/wiki/Windows_Server_2019" title="Windows Server 2019">Windows Server 2019</a></li>
<li><b>19h1</b> � <a href="https://betawiki.net/wiki/Windows_10_May_2019_Update" title="Windows 10 May 2019 Update">Windows 10 May 2019 Update</a>, <a href="https://betawiki.net/wiki/Windows_10_November_2019_Update" title="Windows 10 November 2019 Update">Windows 10 November 2019 Update</a></li>
<li><b>vb</b> (Vibranium) � <a href="https://betawiki.net/wiki/Windows_10_May_2020_Update" title="Windows 10 May 2020 Update">Windows 10 May 2020 Update</a> and later cumulative updates</li>
<li><b>mn</b> (<a href="https://betawiki.net/wiki/Manganese" title="Manganese">Manganese</a>)</li>
<li><b>fe</b> (<a href="https://betawiki.net/wiki/Iron" title="Iron">Iron</a>) � <a href="https://betawiki.net/wiki/Windows_Server_2022" title="Windows Server 2022">Windows Server 2022</a></li>
<li><b>co</b> (<a href="https://betawiki.net/wiki/Cobalt" title="Cobalt">Cobalt</a>) � <a href="https://betawiki.net/wiki/Windows_11_(original_release)" title="Windows 11 (original release)">Windows 11 (original release)</a></li>
<li><b>ni</b> (<a href="https://betawiki.net/wiki/Nickel" title="Nickel">Nickel</a>) � <a href="https://betawiki.net/wiki/Windows_11_2022_Update" title="Windows 11 2022 Update">Windows 11 2022 Update</a>, <a href="https://betawiki.net/wiki/Windows_11_2023_Update" title="Windows 11 2023 Update">Windows 11 2023 Update</a></li>
<li><b>zn</b> (<a href="https://betawiki.net/wiki/Zinc" title="Zinc">Zinc</a>) � <a href="https://betawiki.net/wiki/Windows_Server,_version_23H2" title="Windows Server, version 23H2">Windows Server, version 23H2</a></li>
<li><b>ge</b> (<a href="https://betawiki.net/wiki/Germanium" title="Germanium">Germanium</a>) � <a href="https://betawiki.net/wiki/Windows_11_2024_Update" title="Windows 11 2024 Update">Windows 11 2024 Update</a>, <a href="https://betawiki.net/wiki/Windows_Server_2025" title="Windows Server 2025">Windows Server 2025</a></li></ul>
<h4><span class="mw-headline" id="Branch_prefixes_used_by_other_teams">Branch prefixes used by other teams</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=6" class="mw-editsection-visualeditor" title="Edit section: Branch prefixes used by other teams">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=6&amp;veaction=editsource" title="Edit section: Branch prefixes used by other teams">edit source</a><span class="mw-editsection-bracket">]</span></span></h4>
<p>Some teams that use the Windows codebase but are formally separate from Windows releases also use their own branch prefixes:  
</p>
<ul><li><b>rd</b> (Red Dog) � <a href="https://en.wikipedia.org/wiki/Microsoft_Azure" class="extiw" title="w:Microsoft Azure">Azure</a></li>
<li><b>oc</b> � OneCore</li>
<li><b>xb</b> � <a href="https://en.wikipedia.org/wiki/Xbox" class="extiw" title="w:Xbox">Xbox</a></li></ul>
<h2><span class="mw-headline" id="See_also">See also</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=7" class="mw-editsection-visualeditor" title="Edit section: See also">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=7&amp;veaction=editsource" title="Edit section: See also">edit source</a><span class="mw-editsection-bracket">]</span></span></h2>
<ul><li><a href="https://betawiki.net/wiki/Build_tag" title="Build tag">Build tag</a></li></ul>
<h2><span class="mw-headline" id="Notes">Notes</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=8" class="mw-editsection-visualeditor" title="Edit section: Notes">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=8&amp;veaction=editsource" title="Edit section: Notes">edit source</a><span class="mw-editsection-bracket">]</span></span></h2>
<style data-mw-deduplicate="TemplateStyles:r231718">.mw-parser-output .reflist{font-size:90%;margin-bottom:0.5em;list-style-type:decimal}.mw-parser-output .reflist .references{font-size:100%;margin-bottom:0;list-style-type:inherit}.mw-parser-output .reflist-columns-2{column-width:30em}.mw-parser-output .reflist-columns-3{column-width:25em}.mw-parser-output .reflist-columns{margin-top:0.3em}.mw-parser-output .reflist-columns ol{margin-top:0}.mw-parser-output .reflist-columns li{page-break-inside:avoid;break-inside:avoid-column}.mw-parser-output .reflist-upper-alpha{list-style-type:upper-alpha}.mw-parser-output .reflist-upper-roman{list-style-type:upper-roman}.mw-parser-output .reflist-lower-alpha{list-style-type:lower-alpha}.mw-parser-output .reflist-lower-greek{list-style-type:lower-greek}.mw-parser-output .reflist-lower-roman{list-style-type:lower-roman}</style><div class="reflist reflist-lower-alpha">
<div class="mw-references-wrap"><ol class="references">
<li id="cite_note-1"><span class="mw-cite-backlink"><a href="#cite_ref-1" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text">For example, build <code><a href="https://betawiki.net/wiki/Windows_Longhorn_build_4067_(private/lddm_dev_tech(davidmo))" title="Windows Longhorn build 4067 (private/lddm dev tech(davidmo))">6.0.4067.private/lddm_dev_tech(davidmo).040212-1646</a></code> is a private build initiated by the <code>davidmo</code> user.</span>
</li>
<li id="cite_note-2"><span class="mw-cite-backlink"><a href="#cite_ref-2" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text">Some builds such as <code><a href="https://betawiki.net/wiki/Windows_Longhorn_build_4002_(Lab06_N)" title="Windows Longhorn build 4002 (Lab06 N)">6.0.4002.Lab06_N(ntvbl06).030108-1926</a></code> and <code><a href="https://betawiki.net/wiki/Windows_7_build_6469" title="Windows 7 build 6469">6.1.6469.fbl_find_dev(wexbuild).071002-1531</a></code> are compiled as private builds but were built by an official build lab machine account.</span>
</li>
<li id="cite_note-3"><span class="mw-cite-backlink"><a href="#cite_ref-3" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text">This
 lab still compiled client builds even though it worked on server 
components as the build process does not distinguish between client and 
server SKUs.</span>
</li>
<li id="cite_note-8"><span class="mw-cite-backlink"><a href="#cite_ref-8" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text"><code>fs</code> branches were used in parallel with <code>rs</code> branches.</span>
</li>
</ol></div></div>
<h2><span class="mw-headline" id="References">References</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=9" class="mw-editsection-visualeditor" title="Edit section: References">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=9&amp;veaction=editsource" title="Edit section: References">edit source</a><span class="mw-editsection-bracket">]</span></span></h2>
<link rel="mw-deduplicated-inline-style" href="mw-data:TemplateStyles:r231718"><div class="reflist">
<div class="mw-references-wrap"><ol class="references">
<li id="cite_note-4"><span class="mw-cite-backlink"><a href="#cite_ref-4" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text">Chen, Raymond. <a rel="nofollow" class="external text" href="https://devblogs.microsoft.com/oldnewthing/20130411-00/?p=4693">The importance of having a review panel of twelve-year-old boys, episode 2</a>, <i>The Old New Thing</i>. 11 April 2013.</span>
</li>
<li id="cite_note-5"><span class="mw-cite-backlink"><a href="#cite_ref-5" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text"><a href="https://betawiki.net/wiki/Windows_10_build_21298_(rsmaster)" class="mw-redirect" title="Windows 10 build 21298 (rsmaster)">Windows 10 build 21298 (rsmaster)</a></span>
</li>
<li id="cite_note-6"><span class="mw-cite-backlink"><a href="#cite_ref-6" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text">Brown, Shelby. <a rel="nofollow" class="external text" href="https://www.cnet.com/tech/computing/microsofts-github-is-removing-coding-terms-like-master-and-slave/">Microsoft's GitHub is removing coding terms like "master" and "slave"</a>, <i>CNET</i>. 27 July 2020.</span>
</li>
<li id="cite_note-7"><span class="mw-cite-backlink"><a href="#cite_ref-7" aria-label="Jump up" title="Jump up">?</a></span> <span class="reference-text"><a rel="nofollow" class="external text" href="https://sfconservancy.org/news/2020/jun/23/gitbranchname/">Regarding Git and Branch Naming</a>, <i>Software Freedom Conservancy</i>. 23 June 2020.</span>
</li>
</ol></div></div>
<h2><span class="mw-headline" id="External_links">External links</span><span class="mw-editsection"><span class="mw-editsection-bracket">[</span><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit&amp;section=10" class="mw-editsection-visualeditor" title="Edit section: External links">edit</a><span class="mw-editsection-divider"> | </span><a href="https://betawiki.net/index.php?title=Build_lab&amp;section=10&amp;veaction=editsource" title="Edit section: External links">edit source</a><span class="mw-editsection-bracket">]</span></span></h2>
<ul><li><a rel="nofollow" class="external text" href="https://longhorn.ms/vbl/"><i>Experience Longhorn Project</i> article on virtual build labs</a></li></ul>
<!-- 
NewPP limit report
Cached time: 20240615081151
Cache expiry: 86400
Reduced expiry: false
Complications: [show-toc]
CPU time usage: 0.091 seconds
Real time usage: 0.107 seconds
Preprocessor visited node count: 421/1000000
Post-expand include size: 1389/2097152 bytes
Template argument size: 981/2097152 bytes
Highest expansion depth: 9/100
Expensive parser function count: 0/100
Unstrip recursion depth: 0/20
Unstrip post-expand size: 4923/5000000 bytes
Lua time usage: 0.005/7.000 seconds
Lua memory usage: 549152/52428800 bytes
-->
<!--
Transclusion expansion time report (%,ms,calls,template)
100.00%   75.480      1 -total
 70.23%   53.006      1 Template:Notelist
 69.29%   52.303      2 Template:Reflist
 17.82%   13.449      4 Template:Efn
  6.38%    4.813      3 Template:Main_other
-->

<!-- Saved in parser cache with key betawiki:pcache:idhash:27048-0!canonical and timestamp 20240615081151 and revision id 332779.
 -->
</div>
<div class="printfooter" data-nosnippet="">Retrieved from "<a dir="ltr" href="https://betawiki.net/index.php?title=Build_lab&amp;oldid=332779">https://betawiki.net/index.php?title=Build_lab&amp;oldid=332779</a>"</div></div>
		<div id="catlinks" class="catlinks" data-mw="interface"><div id="mw-normal-catlinks" class="mw-normal-catlinks"><a href="https://betawiki.net/wiki/Special:Categories" title="Special:Categories">Category</a>: <ul><li><a href="https://betawiki.net/wiki/Category:Microsoft" title="Category:Microsoft">Microsoft</a></li></ul></div></div>
	</div>
</div>
<div id="mw-data-after-content">
	<div class="mw-cookiewarning-container"><div class="mw-cookiewarning-text"><span>Cookies help us deliver our services. By using our services, you agree to our use of cookies.</span></div><form method="POST"><div class="oo-ui-layout oo-ui-horizontalLayout"><span class="oo-ui-widget oo-ui-widget-enabled oo-ui-inputWidget oo-ui-buttonElement oo-ui-buttonElement-framed oo-ui-labelElement oo-ui-flaggedElement-primary oo-ui-flaggedElement-progressive oo-ui-buttonInputWidget"><button type="submit" tabindex="0" name="disablecookiewarning" value="OK" class="oo-ui-inputWidget-input oo-ui-buttonElement-button"><span class="oo-ui-iconElement-icon oo-ui-iconElement-noIcon oo-ui-image-invert"></span><span class="oo-ui-labelElement-label">OK</span><span class="oo-ui-indicatorElement-indicator oo-ui-indicatorElement-noIndicator oo-ui-image-invert"></span></button></span></div></form></div>
</div>

<div id="mw-navigation">
	<h2></h2>
	<div id="mw-head">
		

<nav id="p-personal" class="vector-menu mw-portlet mw-portlet-personal vector-user-menu-legacy" aria-labelledby="p-personal-label" role="navigation">
	<h3 id="p-personal-label" class="vector-menu-heading ">
		<span class="vector-menu-heading-label">Personal tools</span>
	</h3>
	<div class="vector-menu-content">
		
		<ul class="vector-menu-content-list"><li id="pt-anonuserpage" class="mw-list-item">Not logged in</li><li id="pt-anontalk" class="mw-list-item"><a href="https://betawiki.net/wiki/Special:MyTalk" title="Discussion about edits from this IP address [Alt+Shift+n]" accesskey="n">Talk</a></li><li id="pt-anoncontribs" class="mw-list-item"><a href="https://betawiki.net/wiki/Special:MyContributions" title="A list of edits made from this IP address [Alt+Shift+y]" accesskey="y">Contributions</a></li><li id="pt-createaccount" class="mw-list-item"><a href="https://betawiki.net/index.php?title=Special:CreateAccount&amp;returnto=Build+lab" title="You are encouraged to create an account and log in; however, it is not mandatory">Create account</a></li><li id="pt-login" class="mw-list-item"><a href="https://betawiki.net/index.php?title=Special:UserLogin&amp;returnto=Build+lab" title="You are encouraged to log in; however, it is not mandatory [Alt+Shift+o]" accesskey="o">Log in</a></li></ul>
		
	</div>
</nav>

		<div id="left-navigation">
			

<nav id="p-namespaces" class="vector-menu mw-portlet mw-portlet-namespaces vector-menu-tabs vector-menu-tabs-legacy" aria-labelledby="p-namespaces-label" role="navigation">
	<h3 id="p-namespaces-label" class="vector-menu-heading ">
		<span class="vector-menu-heading-label">Namespaces</span>
	</h3>
	<div class="vector-menu-content">
		
		<ul class="vector-menu-content-list"><li id="ca-nstab-main" class="selected mw-list-item"><a href="https://betawiki.net/wiki/Build_lab" title="View the content page [Alt+Shift+c]" accesskey="c">Page</a></li><li id="ca-talk" class="new mw-list-item"><a href="https://betawiki.net/index.php?title=Talk:Build_lab&amp;action=edit&amp;redlink=1" rel="discussion" title="Discussion about the content page (page does not exist) [Alt+Shift+t]" accesskey="t">Discussion</a></li></ul>
		
	</div>
</nav>

			

<nav id="p-variants" class="vector-menu mw-portlet mw-portlet-variants emptyPortlet vector-menu-dropdown" aria-labelledby="p-variants-label" role="navigation">
	<input type="checkbox" id="p-variants-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-p-variants" class="vector-menu-checkbox" aria-labelledby="p-variants-label">
	<label id="p-variants-label" aria-label="Change language variant" class="vector-menu-heading ">
		<span class="vector-menu-heading-label">English</span>
	</label>
	<div class="vector-menu-content">
		
		<ul class="vector-menu-content-list"></ul>
		
	</div>
</nav>

		</div>
		<div id="right-navigation">
			

<nav id="p-views" class="vector-menu mw-portlet mw-portlet-views vector-menu-tabs vector-menu-tabs-legacy" aria-labelledby="p-views-label" role="navigation">
	<h3 id="p-views-label" class="vector-menu-heading ">
		<span class="vector-menu-heading-label">Views</span>
	</h3>
	<div class="vector-menu-content">
		
		<ul class="vector-menu-content-list"><li id="ca-view" class="selected mw-list-item"><a href="https://betawiki.net/wiki/Build_lab">Read</a></li><li id="ca-ve-edit" class="mw-list-item"><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=edit" title="Edit this page [Alt+Shift+v]" accesskey="v">Edit</a></li><li id="ca-edit" class="collapsible mw-list-item"><a href="https://betawiki.net/index.php?title=Build_lab&amp;veaction=editsource" title="Edit this page [Alt+Shift+e]" accesskey="e">Edit source</a></li><li id="ca-history" class="mw-list-item"><a href="https://betawiki.net/index.php?title=Build_lab&amp;action=history" title="Past revisions of this page [Alt+Shift+h]" accesskey="h">View history</a></li></ul>
		
	</div>
</nav>

			

<nav id="p-cactions" class="vector-menu mw-portlet mw-portlet-cactions emptyPortlet vector-menu-dropdown" aria-labelledby="p-cactions-label" role="navigation" title="More options">
	<input type="checkbox" id="p-cactions-checkbox" role="button" aria-haspopup="true" data-event-name="ui.dropdown-p-cactions" class="vector-menu-checkbox" aria-labelledby="p-cactions-label">
	<label id="p-cactions-label" class="vector-menu-heading ">
		<span class="vector-menu-heading-label">More</span>
	</label>
	<div class="vector-menu-content">
		
		<ul class="vector-menu-content-list"></ul>
		
	</div>
</nav>

			
<div id="p-search" role="search" class="vector-search-box-vue  vector-search-box-show-thumbnail vector-search-box-auto-expand-width vector-search-box">
	<div>
			<h3>
				<label for="searchInput">Search</label>
			</h3>
		<form action="/index.php" id="searchform" class="vector-search-box-form">
			<div id="simpleSearch" class="vector-search-box-inner" data-search-loc="header-navigation">
				<input class="vector-search-box-input" type="search" name="search" placeholder="Search BetaWiki" aria-label="Search BetaWiki" autocapitalize="sentences" title="Search BetaWiki [Alt+Shift+f]" accesskey="f" id="searchInput">
				<input type="hidden" name="title" value="Special:Search">
				<input id="mw-searchButton" class="searchButton mw-fallbackSearchButton" type="submit" name="fulltext" title="Search the pages for this text" value="">
				<input id="searchButton" class="searchButton" type="submit" name="go" title="Go to a page with this exact name if it exists" value="">
			</div>
		</form>
	</div>
</div>

		</div>
	</div>
	

<div id="mw-panel">
	<div id="p-logo" role="banner">
		<a class="mw-wiki-logo" href="https://betawiki.net/wiki/Main_Page" title=""></a>
	</div>
	

<nav id="p-navigation" class="vector-menu mw-portlet mw-portlet-navigation vector-menu-portal portal" aria-labelledby="p-navigation-label" role="navigation">
	<h3 id="p-navigation-label" class="vector-menu-heading ">
		<span class="vector-menu-heading-label">Navigation</span>
	</h3>
	<div class="vector-menu-content">
		
		<ul class="vector-menu-content-list"><li id="n-mainpage-description" class="mw-list-item"><a href="https://betawiki.net/wiki/Main_Page" title="Visit the main page [Alt+Shift+z]" accesskey="z">Main page</a></li><li id="n-recentchanges" class="mw-list-item"><a href="https://betawiki.net/wiki/Special:RecentChanges" title="A list of recent changes in the wiki [Alt+Shift+r]" accesskey="r">Recent changes</a></li><li id="n-randompage" class="mw-list-item"><a href="https://betawiki.net/wiki/Special:Random" title="Load a random page [Alt+Shift+x]" accesskey="x">Random page</a></li><li id="n-portal" class="mw-list-item"><a href="https://betawiki.net/wiki/BetaWiki:Community_portal" title="About the project, what you can do, where to find things">Community portal</a></li><li id="n-Administrators'-noticeboard" class="mw-list-item"><a href="https://betawiki.net/wiki/BetaWiki:Administrators%27_noticeboard">Administrators' noticeboard</a></li><li id="n-Discord" class="mw-list-item"><a href="https://discord.gg/XPz5Zm42tR" rel="nofollow">Discord</a></li><li id="n-Guidelines" class="mw-list-item"><a href="https://betawiki.net/wiki/BetaWiki:Guidelines">Guidelines</a></li><li id="n-help" class="mw-list-item"><a href="https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents" title="The place to find out">Help</a></li></ul>
		
	</div>
</nav>

	

<nav id="p-tb" class="vector-menu mw-portlet mw-portlet-tb vector-menu-portal portal" aria-labelledby="p-tb-label" role="navigation">
	<h3 id="p-tb-label" class="vector-menu-heading ">
		<span class="vector-menu-heading-label">Tools</span>
	</h3>
	<div class="vector-menu-content">
		
		<ul class="vector-menu-content-list"><li id="t-whatlinkshere" class="mw-list-item"><a href="https://betawiki.net/wiki/Special:WhatLinksHere/Build_lab" title="A list of all wiki pages that link here [Alt+Shift+j]" accesskey="j">What links here</a></li><li id="t-recentchangeslinked" class="mw-list-item"><a href="https://betawiki.net/wiki/Special:RecentChangesLinked/Build_lab" rel="nofollow" title="Recent changes in pages linked from this page [Alt+Shift+k]" accesskey="k">Related changes</a></li><li id="t-specialpages" class="mw-list-item"><a href="https://betawiki.net/wiki/Special:SpecialPages" title="A list of all special pages [Alt+Shift+q]" accesskey="q">Special pages</a></li><li id="t-print" class="mw-list-item"><a href="javascript:print();" rel="alternate" title="Printable version of this page [Alt+Shift+p]" accesskey="p">Printable version</a></li><li id="t-permalink" class="mw-list-item"><a href="https://betawiki.net/index.php?title=Build_lab&amp;oldid=332779" title="Permanent link to this revision of this page">Permanent link</a></li><li id="t-info" class="mw-list-item"><a href="https://betawiki.net/index.php?title=Build_lab&amp;action=info" title="More information about this page">Page information</a></li></ul>
		
	</div>
</nav>

	
</div>

</div>

<footer id="footer" class="mw-footer" role="contentinfo">
	<ul id="footer-info">
	<li id="footer-info-lastmod"> This page was last edited on 17 May 2024, at 07:39.</li>
	<li id="footer-info-copyright">Content is available under <a class="external" rel="nofollow" href="https://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International</a> unless otherwise noted.</li>
</ul>

	<ul id="footer-places">
	<li id="footer-places-privacy"><a href="https://betawiki.net/wiki/BetaWiki:Privacy_policy">Privacy policy</a></li>
	<li id="footer-places-about"><a href="https://betawiki.net/wiki/BetaWiki:About">About BetaWiki</a></li>
	<li id="footer-places-disclaimer"><a href="https://betawiki.net/wiki/BetaWiki:General_disclaimer">Disclaimers</a></li>
	<li id="footer-places-mobileview"><a href="https://betawiki.net/index.php?title=Build_lab&amp;mobileaction=toggle_view_mobile" class="noprint stopMobileRedirectToggle">Mobile view</a></li>
</ul>

	<ul id="footer-icons" class="noprint">
	<li id="footer-copyrightico"><a href="https://creativecommons.org/licenses/by-sa/4.0/"><img src="Build%20lab%20-%20BetaWiki_files/88x31.png" alt="Creative Commons Attribution-ShareAlike 4.0 International" width="88" height="31" loading="lazy"></a></li>
	<li id="footer-poweredbyico"><a href="https://www.mediawiki.org/"><img src="Build%20lab%20-%20BetaWiki_files/poweredby_mediawiki_88x31.png" alt="Powered by MediaWiki" srcset="Build%20lab%20-%20BetaWiki_files/poweredby_mediawiki_132x47.png 1.5x, Build%20lab%20-%20BetaWiki_files/poweredby_mediawiki_176x62.png 2x" width="88" height="31" loading="lazy"></a></li>
</ul>

</footer>

<script>(RLQ=window.RLQ||[]).push(function(){mw.config.set({"wgPageParseReport":{"limitreport":{"cputime":"0.091","walltime":"0.107","ppvisitednodes":{"value":421,"limit":1000000},"postexpandincludesize":{"value":1389,"limit":2097152},"templateargumentsize":{"value":981,"limit":2097152},"expansiondepth":{"value":9,"limit":100},"expensivefunctioncount":{"value":0,"limit":100},"unstrip-depth":{"value":0,"limit":20},"unstrip-size":{"value":4923,"limit":5000000},"timingprofile":["100.00%   75.480      1 -total"," 70.23%   53.006      1 Template:Notelist"," 69.29%   52.303      2 Template:Reflist"," 17.82%   13.449      4 Template:Efn","  6.38%    4.813      3 Template:Main_other"]},"scribunto":{"limitreport-timeusage":{"value":"0.005","limit":"7.000"},"limitreport-memusage":{"value":549152,"limit":52428800}},"cachereport":{"timestamp":"20240615081151","ttl":86400,"transientcontent":false}}});mw.config.set({"wgBackendResponseTime":178});});</script>

</body></html>