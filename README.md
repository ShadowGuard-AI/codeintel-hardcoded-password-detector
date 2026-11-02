![Night street with no lettering: one kettle near and large in the nearest lit window with thin steam rising, a corner lantern, an owl on a roof ridge, cups on sills in two other lit windows, dark houses, and a thin moon](intro-banner.png)

# codeintel-Hardcoded-Password-Detector

Night watch log treatment: the title is set in Bungee on a coffee black plate ruled as a night watch log giving the hour, with a small kettle beside this first part of the page only, and the kettle stays at punctuation size as the section marker throughout.

![One kettle on a small stove ring: round body, short spout, plain handle, clear lid, diner night neon on the lit side, chrome rim and handle, coffee black shadow side, and one small pink enamel chip on the lid, with the name in the night watch log hand below](logo.png)

![One street at 3 a.m.: most windows dark, a few lit, a kettle in the nearest lit window on its stove with thin steam, cups on the sill, a wall clock at the small hours, an owl on a roof ridge, a lantern at the corner, a distant sign giving neon light only, and the title once on the watch log board by the lantern](banner.png)

![Night street in three bands: lit windows change rarely as one goes dark and later another lights, an owl on a roof ridge blinks at long intervals, and a kettle in the nearest window gives a thin line of steam that rises, thins, fades, and thickens briefly when the kettle sings](scene.svg)


A command-line tool that scans code for hardcoded passwords and API keys using regex and entropy analysis. Found values are masked in console output and in the log file: reports show the file, key name, value length, and entropy, never the value itself. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

> **Watch log slip, on entropy.** Entropy does not act as a gate here: the two patterns decide the finds, every match is reported at once, and the entropy figure is a note added afterwards, warning past the threshold that a find may be a false positive.


![Major separator: an owl eyes blink at the centre of the rule](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-hardcoded-password-detector`

> **Watch log slip, flagged in place.** The install line above reads git clone https://github.com/ShadowStrikeHQ/codeintel-hardcoded-password-detector, naming ShadowStrikeHQ in place of ShadowGuard-AI. It is preserved exactly as printed and flagged here, never silently fixed.


![Minor separator: an owl eyes blink at the centre of the rule](sep-light.svg)

## Usage
`./codeintel-hardcoded-password-detector [params]`


![Major separator: an owl eyes blink at the centre of the rule](sep-heavy.svg)

## Parameters
- `-h`: Show help message and exit
- `-v`: Enable verbose logging.
- `-e`: Entropy threshold for flagging potential secrets.  Defaults to 4.0.
- `-l`: Path to log file. If not provided, logs to stdout


![Minor separator: an owl eyes blink at the centre of the rule](sep-light.svg)

## License
Copyright (c) ShadowStrikeHQ

> **Watch log slip, flagged in place.** The closing line above reads Copyright (c) ShadowStrikeHQ, while the repository LICENSE file carries the MIT License. Both stand as printed; neither is changed to suit the other.
