KODUCK — V1.1
BAD DRAWINGS. GOOD CAMERA.

V1.1 CHANGES
Faint facial edges and short feature lines survive better in soft light.
BAD uses a fine pen; WORSE uses wobbling, doubled pen lines; TERRIBLE uses
a thicker, more angular marker. All modes preserve small feature strokes.
The output uses solid black ink on the same plain off-white paper, with
no grey shading. The offline app cache is updated to version 1.1.

LAPTOP
Open index.html in Chrome and allow camera access. No installation,
terminal, build tools, server or internet is needed for this file mode.
The separately supplied KODUCK.html is the same standalone application.

iPHONE / INSTALLABLE PWA
The five app files in this folder must be available together at an HTTPS
static address for first installation. Open that address in Safari, wait
for OFFLINE READY, then use Share > Add to Home Screen. Launch the icon
and allow the camera. It can then reload and run without the internet.
An HTML file opened from the iPhone Files app cannot install a camera PWA.
This download is the complete app package; it has not been hosted online.
No backend, server-side program, external library or API is used.

USE
FLIP switches lenses. The middle button captures the processed drawing.
SAVE downloads a PNG on a laptop. On iPhone it opens the native file sheet;
choose Save Image if available, or press and hold the captured sketch.
RETAKE reopens the camera. Front-camera saves match the mirrored preview.
BAD / WORSE / TERRIBLE changes the amount of simplification and wonkiness.
A face fairly close to the camera, good light and a plain background work
best. This is a local contour-drawing effect, not an AI caricature model.

PRIVACY
Only app files are fetched for installation. Camera frames stay in memory
on the device. There are no uploads, analytics, accounts or galleries.
No microphone permission is requested. The camera is released when you
capture a drawing or put the app in the background. Saving is your action.
Only the processed drawing is exported; the normal camera image is never
saved. Browser removal of app data also removes its offline cache.

FILES
index.html            Complete application, styles and sketch processing
manifest.webmanifest  Installable app metadata
sw.js                 Offline app cache
icon-192.png          App / Apple touch icon
icon-512.png          App / maskable icon

VALIDATION
JavaScript syntax checked. Thirty automated checks passed in Chrome 136
with a test video camera and simulated front/back lenses. These included
permission denial, continuous processing, switching, identical preview
and capture, PNG download, retake, file:// opening, offline reload, local
asset caching and no external network requests. Upgrading the offline
cache from v1.0 to v1.1 was also verified. The native iPhone save
path was checked with a simulated save sheet.
Normal and low-contrast portraits were compared using identical inputs;
the three modes also passed checks for visibly different ink coverage.
Measured on the test machine: about 20 FPS, median sketch processing 11 ms.
Device performance varies; processing resolution adapts automatically.
Physical iPhone cameras and Safari have not been verified. The WebKit
test engine could not run because this environment lacks its system
libraries. Browser and OS permission settings still apply.
