# Change Log

### Future Development
New version are avaible on https://github.com/ingrammicro/puzzle-publisher

##  Version 8.0.0 (12 Aug 2019)
- globally refactored to stabilize mouse hover event support
- show all layer shard style in Element Inspector (not only for text layers)

##  Version 7.2.4 (12 Aug 2019)
- fixed exporting of library symbols information

##  Version 7.2.3 (12 Aug 2019)
- fixed modal positioning in embedded mode
- fixed back navigation for modal opened by direct URL

##  Version 7.2.2 (31 Jul 2019)
- fixed window.open() issue in Safari

##  Version 7.2.1 (29 Jul 2019)
- Fixed overlays in modal behaviour
- Added keyboard shortcuts Cmd+Alt+E (Export) and Cmd+Alt+P (Publish)

##  Version 7.2.0 (25 Jul 2019)
- Added experimental library switcher to inspector viewer
- Fixed vertical scrolling of large modals

##  Version 7.1.1 (19 Jul 2019)
- Several fixes in overlays support

##  Version 7.1.0 (18 Jul 2019)
- Improved Element Inspector
- Support for links between library symbols and libary artboards (you can put shared overlays into library)

##  Version 7.0.0 (16 Jul 2019)
- Redesigned regular page and modal dialogs centering
- Moved Element Inspector to right sidebar (see https://raw.githubusercontent.com/MaxBazarov/exporter/master/tests/Link-ModalArtboard/Screenshot.png)

##  Version 6.4.2 (11 Jul 2019)
- Fixed external link in overlay initiator
- Click outside of modal closes it

##  Version 6.4.1 (10 Jul 2019)
- One more fix for hover overlays
- Improved content caching tweaks

##  Version 6.4.0 (10 Jul 2019)
- Improved hover overlays
- Added static content version postfix to publishing procedure (to improve caching on HTTPD)

##  Version 6.3.5 (9 Jul 2019)
- Fixed positioning of overlay called from other overlay

##  Version 6.3.4 (8 Jul 2019)
- Fixed publishing procedure for versioned mockups

##  Version 6.3.3 (5 Jul 2019)
- Fixed publishing procedure for versioned mockups

##  Version 6.3.2 (4 Jul 2019)
- Force overlay image loading (critical for low bandwith connection)

##  Version 6.3.1 (1 Jul 2019)
- Fixed wrong aligment of on-click overlays
- Improved behavour of on-hover overlays for "hotspot top left position" case (See latest example here - https://github.com/MaxBazarov/exporter/blob/master/tests/OverlayOnMouseOver/test.sketch)

##  Version 6.3.0 (1 Jul 2019)
- Experimental support for shared overlay artboards

##  Version 6.2.1 (20 Jun 2019)
- Fixed Artboard Alignment configuration option behaviour
- Renamed "Enable JSON" plugin configuration optio to ""Don't save data for Element Inspector"

##  Version 6.2.0 (19 Jun 2019)
- Support for custom favicon (see https://github.com/MaxBazarov/exporter/tree/master/tests/Favicon)
- Added layer comments (edit in Configure Layer, show in Element Inspector)

##  Version 6.1.1 (17 Jun 2019)
- Added modals and overlays to Element Inspector
- Viewer constructs Layout Grid on the first call, not on page creation

##  Version 6.1.0 (14 Jun 2019)
- Renaming Show Symbols to Element Inspector
- Fixed closing of Element Inspector
- Added shared style info to Element Inspector

##  Version 6.0.1 (12 Jun 2019)
- Returned "overflow: auto;" for modal dialogs to enable scrolling

##  Version 6.0.0 (11 Jun 2019)
- Added "Show symbols" menu option to see shared symbols used on the page
- Added second option to "Show embed code" 

##  Version 5.18.1 (4 Jun 2019)
- Fixed publishing freeze (for some large projects)

##  Version 5.18.0 (3 Jun 2019)
- Publisher creates sub-folders on SFTP server automatically

##  Version 5.17.0 (14 May 2019)
- Hotspot inside an overlay linked to other overlay opens that second overlay on the same position (usefull to switch between single overlay states) 

##  Version 5.16.2 (25 Apr 2019)
- Improved image batch resizing (in order to fix non-completed exports) - Part II

##  Version 5.16.1 (25 Apr 2019)
- Improved image batch resizing (in order to fix non-completed exports)

##  Version 5.16.0 (25 Apr 2019)
- Added "Hotspot top * side overlay positions to Artboard Settings

##  Version 5.15.1 (24 Apr 2019)
- Fixed "Open new browser window" opton for external links

##  Version 5.15.0 (8 Apr 2019)
- Added "Show grid layout" feature (also available on "l" key)
- External links now use "Open in the new window" setting
- Now hotspots show real links on hover, not abstract "#"

##  Version 5.14.1 (5 Apr 2019)
- Executed autoscale on page switching

##  Version 5.14.0 (5 Apr 2019)
- Removed custom handling of "Space" key
- Changed rendering of fixed layes to fix many know issues

##  Version 5.13.2 (30 Mar 2019)
- Switched compression off by default
- Running compressing in sync

##  Version 5.13.1 (29 Mar 2019)
- Corrected compressor permissions
- Running compressing in async

##  Version 5.13.0 (29 Mar 2019)
- Added image compression

##  Version 5.12.0 (28 Mar 2019)
- Added "Show embed code" item to view menu (also available on "e" key)

##  Version 5.11.2 (27 Mar 2019)
- Fixed exporting
- Now custom artboard size is reseting after an exporting

##  Version 5.11.1 (25 Mar 2019)
- Fixed support for custom sizes

##  Version 5.11.0 (22 Mar 2019)
- Added custom height and width settings to Export HTML dialog (also it flatten fixed layers automatically)

##  Version 5.10.2 (18 Mar 2019)
- Improved auto-scale of modal dialogs in FireFox
- Stretched modal dialog shadow on full page

##  Version 5.10.1 (18 Mar 2019)
- Fixed auto-scale for FireFox

##  Version 5.10.0 (14 Mar 2019)
- Add ?embed to prototype URL to hide navigation and show "Scale" icon

##  Version 5.9.2 (13 Mar 2019)
- Improved Auto-Scale feature (thanks to Konstantin Smirnov for the new icon)
- Fixed Set External URL dialog

##  Version 5.9.1 (12 Mar 2019)
- Fixed support for shadow inside a fixed layer

##  Version 5.9.0 (11 Mar 2019)
- Added zooming of large pages (can be disabled in Plugin settings)

##  Version 5.8.1 (11 Mar 2019)
- Fixed rendering of direct link to modal dialog executed by overlay artboard link

##  Version 5.8.0 (1 Mar 2019)
- Overlays calling by hotspot inside a fixed layer also are showing with fixed position (configurable in Artboard Settings)

##  Version 5.7.3 (28 Feb 2019)
- Keep the only one overlay visible
- Hide overlay on primary artboard hide

##  Version 5.7.1 (27 Feb 2019)
- Fixed external links functionality

##  Version 5.7.0 (26 Feb 2019)
- Changed command line API [Description](https://github.com/MaxBazarov/exporter/blob/master/Hints.md#hint4)
- Added new overlay positions [Illustration](https://raw.githubusercontent.com/MaxBazarov/exporter/master/tests/Overlays/Overlay-Positions.png)

##  Version 5.6.0 (21 Feb 2019)
- Added command line API for exporting into HTML [Description](https://github.com/MaxBazarov/exporter/blob/master/Hints.md#hint4)

##  Version 5.5.0 (20 Feb 2019)
- Click outside hotspots highlights all hotspots for a short time
- Improved Path selector UI

##  Version 5.4.0 (15 Feb 2019)
- New ability to show overlay on mouse over [Example](https://github.com/MaxBazarov/exporter/tree/master/tests/OverlayOnMouseOver)
- New ability to align overlay on left, center or right side of source link

##  Version 5.3.2 (7 Feb 2019)
- Changed way to open HTML in browser

##  Version 5.3.1 (1 Feb 2019)
- Fixed issue with nested fixed layers
- Nowu user can specify unexistent folder as Destination Folder

##  Version 5.3.0 (30 Jan 2019)
- Added ability to setup autotransiton time less than 1 second (in form of 0.001)

##  Version 5.2.3 (29 Jan 2019)
- Fixed bugs

##  Version 5.2.2 (23 Jan 2019)
- Fixed bugs
- Added default left+top constrain for float layers

##  Version 5.2.1 (16 Jan 2019)
- Fixed bugs

##  Version 5.2.0 (14 Jan 2019)
- Fuzy logic for top/left fixed panel detection replaced by the new Layer Setting — Overlay Mode

##  Version 5.1.0 (11 Jan 2019)
New features:
- Added URLs for overlay arboards (user can bookmark a page with visible overlay)

##  Version 5.0.1 (9 Jan 2019)
Fixed bugs:
- The default page doesn't show images in full size

##  Version 5.0.0 (30 Dec 2018)
New features:
- Added ability to define any artboard as "Overlay" / Pictures: [One](https://raw.githubusercontent.com/MaxBazarov/exporter/master/tests/FixedLayers/Overlay1.png), [Two](https://raw.githubusercontent.com/MaxBazarov/exporter/master/tests/FixedLayers/Overlay2.png), [Three](https://raw.githubusercontent.com/MaxBazarov/exporter/master/tests/FixedLayers/Overlay3.png)
Fixed bugs:
- Crashes with "layer.slayer.style is undefined" if Export to JSON enabled

##  Version 4.6.0 (28 Dec 2018)
New features:
- Added Configure Layer command to specify layer <div> ID. It can be possible if you want to do some custom JS-based manipulations.
Fixed bugs:
- Expoter detects @MainBackground@ in wrong way

##  Version 4.5.1 (24 Dec 2018)
If some layer name contain @MainBackground@ substring then it's fill color will be used as browser page background (in case of unspecified Custom Background Color setting in Configure Document dialog). 
It can be useful if you have many Sketch files which are using a common background symbol and don't want to define Custom Background Color in the every Sketch file.

##  Version 4.5.0 (20 Dec 2018)
- Totally redesigned hotspots engine (moved from imagemap+jquery to plain DIVs)

##  Version 4.4.1 (15 Dec 2018)
- Bugfixing

##  Version 4.4.0 (13 Dec 2018)
- New plugin global and document local setting to select artboard sorting rule
- Show Exporting errors after the completion
- Ability to disable fixed layers in plugin settings
- Minor improvements

##  Version 4.3.1 (10 Dec 2018)
- Removed hotspot alt/title/hint
- Moved Exporting process to async process to don't freeze UI  (done partially)

##  Version 4.3.0 (4 Dec 2018)
- Added ability to enable page auto-transition (https://github.com/MaxBazarov/exporter/raw/master/tests/PageTransition.sketch)
- Excluded artboards with "External URL" enabled from exporting
- Changed float fixed panel image name generation to fix possible name collisitions

##  Version 4.2.0 (3 Dec 2018)
- Redesigned Export to HTML dialog
- Moved "Open in browser..."  checkbox from Plugin Settings to Export to HTML

##  Version 4.1.0 (30 Nov 2018)
- Added ability to compress PNG files before publishing
- Added artboard sorting by X position 
- Fixed wrong handling of resized symbol hotspots

##  Version 4.0.3 (29 Nov 2018)
- Minor fixes

##  Version 4.0.2 (29 Nov 2018)
- Minor fixes

##  Version 4.0.1 (27 Nov 2018)
- Supported arboards with non-unique names
- "Highlight hotlinks" current mode is common for all pages

##  Version 4.0.0 (26 Nov 2018)
- Redesigned support for layers with "fixed position during scrolling" option enabled (https://github.com/MaxBazarov/exporter/tree/master/tests/FixedLayers)
- Moved to modern jQuery and jQuery plugins

##  Version 3.4.3 (21 Nov 2018)
- Improved Esc key handling

##  Version 3.4.2 (16 Nov 2018)
- Fixed hotspot cursor view in Chrome
- Added exit on Espace key from overlay pages and Gallery

##  Version 3.4.1 (15 Nov 2018)
- Supported two fixed layer usage types (https://github.com/MaxBazarov/exporter/tree/master/tests/FixedLayers)
- Fixes

##  Version 3.4.0 (13 Nov 2018)
- Added plugin settting to disable hotspots highlighting
- Changed hotspot higlighting color
- Many internal improvements
- Fixed external URL artbords
- Totally improved image preloading
- Added image preloading process indicator
- Added limited support for "fixed position while scrolling" (https://github.com/MaxBazarov/exporter/tree/master/tests/FixedLayers)

##  Version 3.3.1 (2 Nov 2018)
- Rollbacked code to 3.2.0 (3.3.0 was too buggy)

##  Version 3.3.0 (1 Nov 2018)
- Added page images preloading
- Hide navigation global plugin setting can be overwritten for specific document

##  Version 3.2.0 (21 Oct 2018)
- Added artboard autoscroll to top (can be disable for some artboard in Configure Artboard)
- Experimental export into JSON (enable in Configure Plugin)

##  Version 3.1.0 (25 Oct 2018)
- Optimized Gallery (pre-generate preview images)

##  Version 3.0.0 (23 Oct 2018)
- Totally refactored hotspot calculation engine to support any Symbol properties overrides

## Version 2.0.1 ( 9 Oct 2018)
- Fixed publishing error handling

## Version 2.0.0 (5 Oct 2018)
- Added publishing

## Version 1.9.5 (4 Oct 2018)
- Workaround for Sketch 52

## Version 1.9.3 (1 Oct 2018)
- Corrected placeholder for version injection

## Version 1.9.2 (23 Sep 2018)
- Added Plugin setting to disable Navigation

## Version 1.9.1 (21 Sep 2018)
- Added command to export selected artboards

## Version 1.8.4 (19 Sep 2018)
- Fixed wrong handling of artboard name with double quote inside

## Version 1.8.3 (19 Sep 2018)
- Set External Link operation can handle multiply selected layers

## Version 1.8.2 (10 Sep 2018)
- Corrected alert messages (thanks to Ale Muñoz)

## Version 1.8.1 (31 Aug 2018)
- Navigation restyle
- Improved Gallery look-n-feel

## Version 1.7.2 (25 Aug 2018)
- Returned back "Export Retina Images" checkbox in Plugin Settings

## Version 1.7.1 (24 Aug 2018)
- Corrected Gallery icon behaviour

## Version 1.7.0 (23 Aug 2018)
- Reworked dialogs
- Added plugin log
- Fixed bugs
- Added experimental Gallery

## Version 1.6.5 (20 Aug 2018)
- Fixed issue with multi-group symbol
- Fixed issue with overided link to external artboard
