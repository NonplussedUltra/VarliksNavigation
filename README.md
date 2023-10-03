# VarliksNavigation
A navigation and coordinate-finding mod for Minecraft.

THE PLAN ---------------------------------------

Varlik's Navigation (VN) is intended to replace the use of F3 to find coordinates in Minecraft with a gameplay-based method that rewards skill and practice.

REAL NAVIGATION -----------------------------------

North-South distance, or latitude, is found by measuring the altitude of a celestial body from the horizon, for instance the noonday sun, or one of the fixed stars. 

East-West distance, or longitude, is found by comparing local time with the time at a fixed spot on Earth. A difference of one degree longitude between two points on the surface of the Earth corresponds to a time difference of fifteen minutes. Local sidereal time is generally fixed by watching for local noon. Historically, the greater problem was to track time at a fixed point, for instance, Greenwich Mean Time. Pendulum clocks do not work at sea, being affected by the pitch and roll of the ship, and salt spray rapidly degrades clockwork mechanisms. A marine chronometer that overcame the many problems of timekeeping at sea was not invented until 1759, and such a precision instrument remained too expensive for many ships for decades thereafter. Prior to the late 19th century, then, navigators turned to the regular motions of the heavens for a predictable timepiece. Though complicated, the motions of the Moon, and of the moons of Jupiter, could be projected well into the future, and the times of notable events compiled into a marine almanac so observations could be correlated with times.

THE MECHANISM -----------------------------

Varlik's Navigation methods are based on observations of the planet Pluvius, which appears to the naked eye as a bright star moving against the fixed background of the sky. Pluvius and its moons can be used to determine latitude and longitude.

North-South distance (z coordinate), or latitude, is found by using the Cross-Staff to sight the horizon and then Pluvius. The angle between them determines your latitude. The more accurately the two are sighted, the more accurate the resulting Z coordinate. After players collect amethyst crystals, they can be used to craft the Sextant, which makes it easier to take accurate sights.

East-West distance (x coordinate) is longitude. It is found by using a Clock and Cross-Staff to sight Pluvius. When Pluvius is sighted with a Clock and Cross-Staff in hand, an image of Pluvius appears. The player must right-click again when Pluvius flickers, indicating the occultation of Pluvius by its moons. The nearer to the flicker the player clicks, the more accurate the sighting and hence the obtained X-coordinate. With the Cross-Staff, this is an inherently inaccurate operation that can only locate the player to within +/- a certain percentage of the world circumference (as defined in config).
With the Sextant, all four moons can be seen and the minigame changes. The moons race around Pluvius at different speeds, and the player must right-click as each one is immersed in or emersed from shadow. The less the overall deviation, the more accurate the obtained X-Coordinate.

THE MINIGAMES ----------------------------
The Latitude Minigame:
With both the Cross-Staff and the Sextant, the trick is to measure Pluvius' distance above the horizon in a target-shooting minigame. The player engages the item, causing the view to zoom in somewhat.

THE ITEMS ---------------------------

Clock - The standard Minecraft clock, with the added function of having to be held in the offhand to measure longitude.

Cross-Staff - A wooden tool used to take astronomical measurements. The materials are accessible, but the instrument is relatively inaccurate.

Sextant - An advanced navigation tool made from brass and crystal. It enables more accurate sightings, although player skill is still a factor.
