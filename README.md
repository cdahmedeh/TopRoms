![TopRoms Logo](./assets/toproms-logo-black.png)

## Welcome to TopRoms

The TopRoms Collection is a curated collection of classic console games focusing on high-quality, notable and popular titles. Contrary to other sets, TopRoms does not aim to be an exhaustive package with every game ever released. Instead, games are hand-picked based on their gameplay quality, historical significance and popularity to find both notable releases and obscure gems.

TopRoms covers a large set of game consoles, handhelds, arcade machines and computers all the way up to the 6th generation. The set had a modest start in 2017 with just a few older systems but has grown massively to cover so much more of gaming history.

My main motive with TopRoms was to provide a more portable package for retro ROMs and one that was more convenient. One of the main issues was hunting for games through a massive list of thousands of entries and that a random pick would likely lead into mediocrity.

## Downloads

| Torrent | Magnet Link |Release Notes | Date | Total Size | MD5 |
| ------- | ------------| ---- | ---- | ---------- | ------ |
| [TopRoms Collection - New Generation Edition](https://github.com/cdahmedeh/TopRoms/raw/refs/heads/main/torrents/TopRoms%20Collection%20-%202025-01-06.torrent) | [Magnet Link](https://raw.githack.com/cdahmedeh/TopRoms/main/magnets/TopRoms%20Collection%20-%202025-01-06.new.html)| [Notes](docs/notes/TR-2025-01-06.md) / [Blog](https://www.cdahmedeh.net/blog/2025/1/7/toproms-enters-a-new-generation) | 2025-01-06 | 1.575 TiB | E2C40C7DEA41050F811E96802561D5FE

## Content

[Sets](./docs/SETS.md) - Sets and Systems included in TopRoms

## Discussions

Have discussions about TopRoms in the new [GitHub Discussions](https://github.com/cdahmedeh/TopRoms/discussions) section above. You can talk about TopRoms here! Make recommendations to be added to the next edition of TopRoms. Share how you use TopRoms with your setup!

## Suggestions

If you have a game to suggest, leave a note in the [GitHub discussions](https://github.com/cdahmedeh/TopRoms/discussions) or email me at toproms@cdahmedeh.net

## Learn More

<details>
<summary><b>History of TopRoms</b></summary>

### History

The project started around 2015, still a personal one. At the time, a Raspberry Pi was being used as an HTPC for the living room TV. The storage was limited due to the small capacity SD card but still wanted to include a decent collection of games to play. Some sets were decently small, for example, the entire NES library fit at around 400 megabytes but even something just slightly ahead like the SNES was much larger exceeding 3 GB. I also wanted to take my retro gaming on the road with my smartphone.

Knowing that complete collections were full of mediocre titles and that only a select few were worth playing, why not include only those? For NES games, for example, it was somewhat easy, since I grew up with that console but the SNES was a bit harder since I never owned one. SNES also had a massive library of well-loved RPGs and I was totally unfamiliar with the genre.

I started to probe various online resources, mostly blogs that had top lists landing with an eventual amalgamation of about 100 titles for each console. The Raspberry Pi was quite weak at the time, and I couldn't go further than the fourth-generation of systems. However, single-board computers were becoming more powerful and my TV was now tethered with a proper PC-based HTPC. It meant that much more powerful systems could be emulated. But I remained lazy and the collection was stagnant.

Around 2016, a then coworker set up a makeshift arcade with a set of tabletop controllers and a small screen in the office's kitchen. Just like my earlier setup, it was using a Raspberry Pi running RetroPie. There was only a tiny collection of games, maybe a total of 20 games that were actually dumped from real cartridges. I suggested to have my collection used and the makeshift arcade was used by so many in the office afterwards, including the CEO who had a fondness for the Atari 2600.

Later, I thought that my project would be useful to others and became public in April 2017. It had a measly ten systems and was quite incomplete, but it caught on nonetheless. I left it untouched for a while thinking nothing of it but I started getting emails about people using the collection for their various setups. I conceded, and in 2021, I began taking the project more seriously. The rest was history.

Now, TopRoms has over 50 systems, with a seemingly massive size of 1.6 TB but this a far-cry from a couple dozen terabytes needed to host complete sets for each of the platforms. The collection was initially hosted on MEGA, but kept exceeding the bandwidth limit. So the collection was moved to a torrent, which really simplified things and made downloading the set more convenient and practical. For me, the most important features are the ability to only select the systems you want, and only download the differences when a new set is available.

</details>

<details>
<summary><b>Curation Process</b></summary>

### Curation

Now, how can I reliably curate a set of quality games and include every game you can think of without having an exhaustive set? Well, this is something I'm keeping as a secret recipe since this is what keeps TopRoms unique. All I can say is that I rely heavily on online resources like blog, top lists, articles on gaming websites, review aggregators, printed magazines and a few other obscure places. I am focused on titles with great gameplay but also best-selling titles and hidden gems. The biggest criteria is not including games for the sake of my own nostalgia or my own picks. Every game choice needs to be backed by someone else.

To ensure the cleanest set possible, all entries are pulled from No-Intro, Redump, Trurip and TOSEC. Arcade games are pulled from publicly available MAME sets that can be found on the Internet Archive or elsewhere. Since many games are released in multiple regions, the choice Is usually US versions but sometimes the European or Japanese versions are better. Care is ensured that the image formats are compatible with popular emulators without the need for extracting ROMs, converting to compatible formats, and if possible, reduce the file sizes.

The curation process has been the most time-consuming and honestly painful part of the process. While some of it is automated with scripts, there is still a significant manual processes to make up for the automation's gaps. Entries are verified against a list I collected based on my research to make sure everything is included. Cleaning up the file names and running the conversions take an inordinate amount of time.

</details>



## Frontends

- [LaunchBox](https://www.launchbox-app.com) - My favourite frontend for desktop PC. Great for handling large collections. Comes with the excellent BigBox big-picture mode. However, quite difficult to set up with a steep learning curve.
- [RetroBat](https://www.retrobat.org) - Wonderful for a living room media-centre setup. Incredibly powerful, various tweaks at your fingertips and beautiful EmulationStation interface. Surprisingly intuitive to set up and pulls metadata and images automatically.
- [Daijishō](https://github.com/TapiocaFox/Daijishou) - An Android front-end for your emulation needs. Probably the most beautiful interface I've seen in a launcher. Great for taking your collection with you on-the-go.
- [ES-DE](https://es-de.org) - A multi-platform front-end for Windows, macOS, Linux and even Android. With a decently easy-to-use scraping.
- [HyperSpin](https://hyperspin-fe.com) - Arguably the most dynamic and visually pleasing interfaces popular with those building their own arcade machines. Incredibly difficult to setup and very steep learning curve.
- [Batocera.linux](https://batocera.org) - An operating system with a front-end designed for portable devices, mainly dedicated emulator handhelds like Anbernic.
- [EmuDeck](https://www.emudeck.com) - Integrates with Steam so that your collection shows up there. Automatically downloads and sets up emulators with basic scraping. Works great on the Steam Deck running SteamOS.

## Resources

- [Emulation General Wiki](emulation.gametechwiki.com/) - A great place to find information about emulators, compatibility and recommendations.
- [Myrient](https://myrient.erista.me) - Finding ROMs was difficult in the past with sketchy websites, slow downloads and malware. A non-profit project that hosts the majority of ROM project collections like No-Intro and Redump.
- [Pleasure Dome](https://pleasuredome.github.io/pleasuredome/) - What started a private tracker for the latest and greatest in ROM sets, especially arcade. Has become a little corner on GitHub with exhaustive packages of MAME and non-MAME sets.
- [Internet Archive](https://archive.org) - A gold-mine of posterity and legacy, not only for ROMs, but classic games of past eras. Books lost to time, movies and so much more. And the Wayback Machine for useful resources that have been dropped from hosting.
- [Video Game History Foundation](https://gamehistory.org) - A tiny non-profit who really care about persevering history and somehow saving lost-media. My favourite efforts was discovering and dumping the games for the defunct Sega Channel and Brenda Ross’ portfolio with art from dropped levels of Sonic 2.
- [Libretro and RetroArch](https://www.libretro.com) - I still remember the last 90s and early 2000s when emulators were all over the place, with feature sets and setup issues unique to each package. Libretro and the associated Libretro became unifying platform for almost all available emulators. Open-source and runs on pretty much any platform you can imagine. Interface is a bit complicated due to the plethora of features and tweaks but pairs excellently with various front-ends.
- [MAME](https://www.mamedev.org) - The grand-father of vintage, emulation and game preservation. Absolutely obsessed with accuracy at any cost with excellent documentation. With pretty much every system imaginable emulated. A front-end is not optional with MAME.

## Similar Projects

Other similar game curation projects on the web:

- [Retrogaming - Les Listes Des Meilleurs Jeux](https://github.com/cosmo0/retrogaming-meilleurs-jeux)
- [Internet Archive - Retro Roms "Best" Set](https://archive.org/details/retro-roms-best-set)
- [Internet Archive - Tiny Best Set: GO!](https://archive.org/details/tiny-best-set-go)
- [reddit - TOP 100 Game Packs](https://www.reddit.com/r/Roms/comments/e5mndq/top_100_game_packs/)
- [Cylum's ROM Sets/Collection Packs](https://pirates-forum.org/Thread-Cylum-s-ROM-Sets-Collection-Packs)
- [aevans0001 - All Killer No Filler Lists](https://www.reddit.com/r/Roms/comments/1nd1i5v/all_killer_no_filler_lists/)

## Transparency

The TopRoms logo was AI-generated.