# WikiMediaExtension3D_Test_GLB_Format

GitHubPage: https://opendem.github.io/WikiMediaExtension3D_Test_GLB_Format/

Test Viewer for the integration of GLB files in the MediaWiki 3D Extension: https://www.mediawiki.org/wiki/Extension:3D

You could choose from different free STL and GLB models, or upload your own data.

Only simple GLB models and KTX2 compression is supported.

Based on three.js 162 for the following reason pointed out by Donmccurdy:
Three.js v163 removed support for WebGL 1, but 3d2png depends on headless-gl, which only supports WebGL 1. Assuming 3D and 3D2PNG should use the same three.js versions for consistency, three.js v162 is used for both now.
