# woff2ttf
Converts WOFF (web) fonts to TrueType (ttf) format

Example

<php

$woffFile = 'awesome_font.woff';
$ttfFile = 'awesome_font.ttf';

WOFF2TTF::convert($woffFile, $ttfFile);
