# Reversed Format Collection

This repository is filled with various notes on various different formats that I've reversed overtime. A lot of these
are provided in
[Rehex](https://github.com/solemnwarning/rehex)'s
[Binary Template](https://solemnwarning.net/rehex/manual/bt.html) format,
which is easily translatable into C/C++ and most other languages.

As noted in the [license](./LICENSE), I'm releasing all of this documentation into the public domain. That said, a
reference or callout wouldn't hurt! ❤️

Contributions are also welcome! Just keep in mind that the plan is to keep *everything* here public domain.

----

## [Acclaim Studios Austin](https://en.wikipedia.org/wiki/Acclaim_Studios_Austin)

### Turok Evolution Engine (2003 - )

Not entirely sure if this engine has another name or not, but it appears to have been developed during Vexx's and Turok
Evolution's development, with the latter being the first game released utilising it.

Supported the Nintendo GameCube, Sony PlayStation 2, Microsoft Xbox and Microsoft Windows.

- [Turok: Evolution](https://en.wikipedia.org/wiki/Turok:_Evolution) (2002)
- [Vexx](https://en.wikipedia.org/wiki/Vexx) (2003)
- [The Red Star](https://hiddenpalace.org/Category:The_Red_Star_prototypes) (Cancelled)
- [100 Bullets](https://hiddenpalace.org/Category:100_Bullets_prototypes) (Cancelled)

| Name | Description        | Status   | URL                              |
|------|--------------------|----------|----------------------------------|
| TRE  | Package format     | **Done** | [Link](asaustin/asaustin_tre.bt) |
| EMI  | Emitter definition | Partial  | [Link](asaustin/asaustin_emi.md) |

## [Appeal S.A.](https://www.mobygames.com/company/appeal-studios-sa)

Developers behind [Outcast](https://www.mobygames.com/game/windows/outcast).

| Name | Description | Status  | Games   | URL                          |
|------|-------------|---------|---------|------------------------------|
| MSH  | Mesh format | Partial | Outcast | [Link](appeal/appeal_msh.bt) |

## [Blitz Games Ltd](https://www.mobygames.com/company/blitz-games-ltd_)

UK-based developer that shut down in 2013.
Developed a number of different games, some of which do seem to share common technology.

### B1 (1998 - 2002)

This is the term we'll use to refer to Blitz's technology used in earlier games from the PlayStation, Nintendo 64 and
Saturn era, starting with Glover.

- Glover (1998)
- Action Man: Operation Extreme (1999)
- Action Man: Destruction X (2000)
- Frogger 2: Swampy's Revenge (2000)
- Titan A.E. (Demo, 2000) (Cancelled)
- Chicken Run (2000)
- Cubix: Robots For Everyone - Race 'N Robots (?) (2001)
- Disney's Lilo & Stitch: Trouble in Paradise (2002)

| Name | Description    | Status                                                                                              | URL                        |
|------|----------------|-----------------------------------------------------------------------------------------------------|----------------------------|
| DAT  | Package format | **Done** ([hashing](https://github.com/OldTimes-Software/hei/blob/master/extras/blitz/blitz.c#L15)) | [Link](blitz/blitz_dat.bt) |
| PSI  | Model format   | Partial                                                                                             | [Link](blitz/blitz_psi.bt) |

## [Core Design](https://en.wikipedia.org/wiki/Core_Design)

![](https://upload.wikimedia.org/wikipedia/en/3/30/Classic_Core_Design_LTD_log.png)

### Herdy Gerdy Engine

Unaware of any proper name for this particular engine. There is some cross-over between this and the engine developed for the cancelled Tomb Raider Anniversary.

#### Games

- [Herdy Gerdy (2002)](https://www.mobygames.com/game/herdy-gerdy)

#### Formats

| Name | Description                             | Status                      | URL                      |
|------|-----------------------------------------|-----------------------------|--------------------------|
| CLU  | Package format                          | **Done**                    | [Link](core/core_clu.bt) |
| HGT  | Texture format ('Herdy Gerdy Texture'?) | Partial (container for BMP) | [Link](core/core_hgt.bt) |
| HGM  | Model format ('Herdy Gerdy Model'?)     | Pending                     | N/A                      |
| GLV  | Level format ('Gerdy Level'?)           | Pending                     | N/A                      |

## [Computer Artworks Ltd.](https://www.mobygames.com/company/computer-artworks-ltd)

Developed two games, [Evolva](https://www.mobygames.com/game/windows/evolva)
and [The Thing](https://www.mobygames.com/game/thing).
Both games appear to be derived from the same in-house technology.

| Name | Description                  | Status                        | Games             | URL                                 |
|------|------------------------------|-------------------------------|-------------------|-------------------------------------|
| 3DF  | Bitmap font descriptor       | Partial                       | The Thing         | [Link](computer-artworks/ca_3df.bt) |
| AN   | Animation data               | Pending                       | The Thing         | N/A                                 |
| BIN  | Entity data                  | Partial                       | The Thing         | [Link](computer-artworks/ca_bin.bt) |
| BT   | Strings                      | **Done**                      | The Thing         | [Link](computer-artworks/ca_bt.bt)  |
| ENT  | Text-based entity descriptor | Pending                       | Evolva            | N/A                                 |
| GEO  | Collision mesh data          | Pending                       | The Thing         | N/A                                 | 
| FX   | Text-based effect descriptor | Pending                       | The Thing         | N/A                                 |
| LVL  | INI level descriptor format  | Pending                       | Evolva, The Thing | N/A                                 |
| MSH  | Mesh data                    | Partial                       | Evolva, The Thing | [Link](computer-artworks/ca_msh.bt) |
| PAK  | ZIP package                  | **Done** (it's a zip :shrug:) | The Thing         | N/A                                 |
| SGH  | 'SceneGraph'                 | Pending                       | Evolva, The Thing | N/A                                 |

## [Gee Whiz! Entertainment](https://www.mobygames.com/company/gee-whiz-entertainment)

| Name | Description    | Status   | Games       | URL                    |
|------|----------------|----------|-------------|------------------------|
| H95  |                | Partial  | Zombie Wars | [Link](geewhiz/h95.md) |
| SB0  | Package format | **Done** | Zombie Wars | [Link](geewhiz/sb0.md) |
| SPR  | Sprite format  | Partial  | Zombie Wars | [Link](geewhiz/spr.md) |

## [Guerrilla Cambridge](https://www.mobygames.com/company/guerrilla-cambridge)

Also known as Millennium Interactive Ltd. and SCE Studio Cambridge.

| Name | Description                       | Status | Games                  | URL                         |
|------|-----------------------------------|--------|------------------------|-----------------------------|
| MWD  | Package format, 'Millennium WAD'? | ...    | C-12: Final Resistance | [Link](millennium/m_mwd.bt) |

## [Infogrames Studios Limited](https://www.mobygames.com/company/infogrames-studios-limited)

Also known as Gremlin Interactive Limited.
Developed games such as Hogs of War, Actua Soccer, Realms of the Haunting and many more.

Didn't really have an engine, but some of their games share some technology.

| Name | Description | Status  | Games             | URL                            |
|------|-------------|---------|-------------------|--------------------------------|
| MIN  | Model data  | Partial | Hogs of War (PSX) | [Link](gremlin/gremlin_min.bt) |

## [Triton](https://www.pouet.net/groups.php?which=161)

Demoscene group.
Essentially the predecessor to Starbreeze.
Responsible for the cancelled [Into the Shadows](https://www.pouet.net/prod.php?which=2588) game.

| Name | Description | Status  | Games            | URL                          |
|------|-------------|---------|------------------|------------------------------|
| HDV  | Mesh data   | Partial | Into the Shadows | [Link](triton/triton_hdv.bt) |

