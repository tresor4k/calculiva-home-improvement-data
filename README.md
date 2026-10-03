# Calculiva home improvement constants register

Version 2026-10-01 · 35 records · published by [Calculiva](https://calculiva.com/data-sources/) · license CC BY 4.0

The sourced trade constants that the home improvement calculators on calculiva.com load, each with
the source it was read from, the date it was last verified and its status. The calculators read
these records when the site is built. A record without a named source, a verification date and a
scope stops that build; so does a `standard` or `market_survey` record without a source URL, and a
`market_survey` record without an expiry date. A `convention` is not required to have a URL.

Not in the register: the calculators' editable default settings (joint width, waste allowance,
pieces per box, curtain fullness, number of coats and the like). They are example inputs that the
user changes, not sourced constants.

## Calculator hubs on calculiva.com that read these records

[Flooring calculators](https://calculiva.com/flooring/) · [Tile calculators](https://calculiva.com/tile/) · [Wallpaper calculators](https://calculiva.com/wallpaper/) · [Wall paneling calculators](https://calculiva.com/wall-paneling/) · [Landscaping calculators](https://calculiva.com/landscaping/) · [Window treatment calculators](https://calculiva.com/windows/)

## Calculators on calculiva.com that read these records

Generated from the rendered pages: a page is listed when it links a source of the record, or when its script carries the record.

| Calculator | Records it reads |
|---|---|
| [calculiva.com/flooring/carpet-flooring-calculator/](https://calculiva.com/flooring/carpet-flooring-calculator/) | `carpet-roll-observations` |
| [calculiva.com/flooring/epoxy-flooring-calculator/](https://calculiva.com/flooring/epoxy-flooring-calculator/) | `epoxy-coverage-observations` |
| [calculiva.com/flooring/flooring-calculator-cost/](https://calculiva.com/flooring/flooring-calculator-cost/) | `flooring-cost-estimator-bases` |
| [calculiva.com/flooring/flooring-calculator/](https://calculiva.com/flooring/flooring-calculator/) | `flooring-joint-checks`, `laminate-layer-guidance` |
| [calculiva.com/flooring/gym-flooring-calculator/](https://calculiva.com/flooring/gym-flooring-calculator/) | `gym-flooring-observations` |
| [calculiva.com/flooring/hardwood-flooring-calculator/](https://calculiva.com/flooring/hardwood-flooring-calculator/) | `hardwood-racking-guidance` |
| [calculiva.com/flooring/laminate-flooring-calculator/](https://calculiva.com/flooring/laminate-flooring-calculator/) | `flooring-joint-checks`, `laminate-layer-guidance` |
| [calculiva.com/landscaping/asphalt-calculator/](https://calculiva.com/landscaping/asphalt-calculator/) | `asphalt-unit-weight-observations` |
| [calculiva.com/landscaping/mulch-calculator/](https://calculiva.com/landscaping/mulch-calculator/) | `mulch-bag-observations`, `mulch-depth-guidance`, `playground-surfacing-cpsc`, `soil-weights-and-sale-units` |
| [calculiva.com/landscaping/sod-calculator/](https://calculiva.com/landscaping/sod-calculator/) | `sod-format-observations`, `sod-installation-guidance`, `sod-plugging-ifas` |
| [calculiva.com/landscaping/soil-calculator/](https://calculiva.com/landscaping/soil-calculator/) | `soil-bag-observations`, `soil-weights-and-sale-units` |
| [calculiva.com/tile/ceiling-tile-calculator/](https://calculiva.com/tile/ceiling-tile-calculator/) | `ceiling-panel-guidance` |
| [calculiva.com/tile/deck-tile-calculator/](https://calculiva.com/tile/deck-tile-calculator/) | `deck-module-guidance` |
| [calculiva.com/tile/grout-calculator/](https://calculiva.com/tile/grout-calculator/) | `grout-coverage-tables`, `grout-joint-practice`, `tile-joint-guidance` |
| [calculiva.com/tile/lowes-tile-calculator/](https://calculiva.com/tile/lowes-tile-calculator/) | `lowes-rectangular-tile` |
| [calculiva.com/tile/mosaic-tile-calculator/](https://calculiva.com/tile/mosaic-tile-calculator/) | `mosaic-sheet-planning` |
| [calculiva.com/tile/pool-waterline-tile-calculator/](https://calculiva.com/tile/pool-waterline-tile-calculator/) | `pool-band-planning` |
| [calculiva.com/tile/shower-tile-calculator/](https://calculiva.com/tile/shower-tile-calculator/) | `tile-joint-guidance` |
| [calculiva.com/tile/tile-calculator/](https://calculiva.com/tile/tile-calculator/) | `herringbone-format-guidance`, `tile-joint-guidance` |
| [calculiva.com/tile/wall-tile-calculator/](https://calculiva.com/tile/wall-tile-calculator/) | `tile-joint-guidance` |
| [calculiva.com/wall-paneling/board-and-batten-calculator/](https://calculiva.com/wall-paneling/board-and-batten-calculator/) | `batten-spacing-conventions`, `lumber-nominal-actual-softwood`, `stock-lengths-us`, `trim-nominal-actual-mdf` |
| [calculiva.com/wall-paneling/picture-frame-molding-calculator/](https://calculiva.com/wall-paneling/picture-frame-molding-calculator/) | `stock-lengths-us`, `trim-nominal-actual-mdf`, `trim-waste-allowance` |
| [calculiva.com/wall-paneling/wainscoting-calculator/](https://calculiva.com/wall-paneling/wainscoting-calculator/) | `lumber-nominal-actual-softwood`, `stock-lengths-us`, `trim-nominal-actual-mdf`, `wainscot-height-conventions` |
| [calculiva.com/wallpaper/painted-paper-wallpaper-calculator/](https://calculiva.com/wallpaper/painted-paper-wallpaper-calculator/) | `painted-paper-wallpaper-observations`, `wallpaper-roll-observations` |
| [calculiva.com/wallpaper/wallpaper-calculator-with-repeat/](https://calculiva.com/wallpaper/wallpaper-calculator-with-repeat/) | `wallpaper-roll-observations` |
| [calculiva.com/wallpaper/wallpaper-calculator-yards/](https://calculiva.com/wallpaper/wallpaper-calculator-yards/) | `painted-paper-wallpaper-observations`, `wallpaper-roll-observations` |
| [calculiva.com/wallpaper/wallpaper-calculator/](https://calculiva.com/wallpaper/wallpaper-calculator/) | `painted-paper-wallpaper-observations`, `wallpaper-roll-observations` |
| [calculiva.com/wallpaper/york-wallpaper-calculator/](https://calculiva.com/wallpaper/york-wallpaper-calculator/) | `york-wallpaper-observations` |
| [calculiva.com/windows/curtain-fabric-calculator/](https://calculiva.com/windows/curtain-fabric-calculator/) | `curtain-measuring-conventions` |
| [calculiva.com/windows/curtain-size-calculator/](https://calculiva.com/windows/curtain-size-calculator/) | `curtain-measuring-conventions` |

## Files

| File | Content | Copy served by calculiva.com |
|---|---|---|
| [`calculiva-home-improvement-constants.csv`](calculiva-home-improvement-constants.csv) | the register: one row per record, with its source, its dates and its status | [csv](https://calculiva.com/data/calculiva-home-improvement-constants.csv) |
| [`calculiva-home-improvement-constants.json`](calculiva-home-improvement-constants.json) | the full records, values included | [json](https://calculiva.com/data/calculiva-home-improvement-constants.json) |
| [`meta/datapackage.json`](meta/datapackage.json) | Frictionless descriptor: license, sources, schema; its resources point to the served copies | [descriptor](https://calculiva.com/data/datapackage.json) |
| [`LICENSE`](LICENSE) | CC BY 4.0 legal code | |

This repository, `calculiva-home-improvement-data`, is generated from the same records as the copies served by
calculiva.com. Nothing in it is edited by hand.

The CSV is a register, not a table of constants: it holds no value and no unit. The values are in
the JSON file, under keys that differ from one record to the next. There is no unit field: where a
key has a unit, its suffix carries it (`_in`, `_ft`, `_sqft`, `_cuyd`, `_lb`, `_usd`, `_percent`
and others).

## Register columns

| Column | Type | Meaning |
|---|---|---|
| `id` | string | Stable identifier of the record; also the key of the full record in the JSON file. |
| `label` | string | What the record holds. |
| `status` | string | standard = taken from a published reference document cited by title and section; market_survey = read on products or tools on a stated date, always with an expiry date; convention = widely repeated, no normative source. |
| `scope` | string | Where the values apply, and where they do not. |
| `source_name` | string | The document, product page or tool the values were read from. |
| `source_url` | string | URL of that source. Empty when the publisher has removed the page since the reading; the JSON record then explains it in source_status. |
| `verified_at` | date | Date the source was last read (ISO 8601). |
| `expires_at` | date | Date after which the record is left out of this dataset until its source is read again. Every market survey has one and a convention may have one; empty when the record does not expire. |
| `sample_size` | integer | Number of products or executions observed, when the record is a survey. |

## The three statuses

- `standard` (3): taken from a published reference document that can be cited by title and section (a product standard, a federal handbook or a published reference table), cited with its reference. The status is assigned by hand in each record and no code checks that a source is normative: read the record's `source_name` and `scope` for the kind of document it is. It does not mean the value is a legal requirement.
- `market_survey` (20): read on products on sale or on tools as they ran, on the stated date. Every one carries an expiry date.
- `convention` (12): widely repeated, with no normative source. Published as a convention, never as a rule. 8 of them carry an expiry date too.

Past its expiry date a record is left out of this dataset at the next export, and the site build
stops until its source has been read again: an expired figure is not shown with an old date.

## Records

| id | status | verified | what it holds |
|---|---|---|---|
| `asphalt-unit-weight-observations` | market_survey | 2026-09-18 | Hot mix asphalt: in-place unit weight, lift thickness rules and what ranking calculators assume |
| `batten-spacing-conventions` | convention | 2026-09-09 | Usual spacing between battens on an interior wall |
| `carpet-roll-observations` | market_survey | 2026-09-10 | Carpet estimators: what they multiply, observed executions |
| `ceiling-panel-guidance` | convention | 2026-09-10 | Suspended ceiling module and border planning |
| `curtain-measuring-conventions` | market_survey | 2026-09-10 | Curtain sizing and drapery yardage conventions as published by the ranking tools and guides, with their executions |
| `deck-module-guidance` | convention | 2026-09-10 | Interlocking deck module planning |
| `epoxy-coverage-observations` | market_survey | 2026-09-10 | Epoxy floor coverage: physical basis and observed estimator rules |
| `flooring-cost-estimator-bases` | market_survey | 2026-09-10 | What ranking flooring cost estimators multiply (observed executions) |
| `flooring-joint-checks` | market_survey | 2026-09-10 | Pergo Classics: example of product-specific plank checks |
| `grout-coverage-tables` | market_survey | 2026-09-25 | Cement grout coverage as published by two manufacturers, and the joint model and powder density each table implies |
| `grout-joint-practice` | convention | 2026-09-25 | Sanded or unsanded cement grout by joint width, caulk instead of grout at changes of plane, and joint width against tile variation, as TCNA answers them |
| `gym-flooring-observations` | market_survey | 2026-09-10 | Gym flooring estimators: what they multiply, observed executions |
| `hardwood-racking-guidance` | market_survey | 2026-09-10 | Somerset SolidPlus racking example and random-length disclosure |
| `herringbone-format-guidance` | market_survey | 2026-09-10 | Rectangular herringbone format examples |
| `laminate-layer-guidance` | market_survey | 2026-09-10 | Pergo Classics layer selection example |
| `lowes-rectangular-tile` | market_survey | 2026-09-10 | Lowe’s rectangular tile: verified faces and sales units |
| `lumber-nominal-actual-softwood` | standard | 2026-09-09 | Nominal and actual dimensions of softwood boards sold in the United States |
| `mosaic-sheet-planning` | convention | 2026-09-10 | Mosaic sheet and chip planning |
| `mulch-bag-observations` | market_survey | 2026-09-25 | Bagged mulch sizes and label instructions of one product line, and what the five ranking mulch calculators assume |
| `mulch-depth-guidance` | convention | 2026-09-25 | Landscape mulch: depth, distance from the trunk, size of the tree ring and topping up, as published by five extension services and two tree programs |
| `painted-paper-wallpaper-observations` | market_survey | 2026-09-10 | Painted Paper roll formats, prices, repeats and the on-page estimator, observed |
| `playground-surfacing-cpsc` | standard | 2026-09-25 | Loose-fill playground surfacing: minimum depths by equipment height, compression of the initial fill, and how far the surfacing extends |
| `pool-band-planning` | convention | 2026-09-10 | Pool waterline band measurement |
| `sod-format-observations` | market_survey | 2026-09-25 | Sod piece and roll sizes, pallet coverage and weight, and the cutting allowance used by the ranking sod calculators |
| `sod-installation-guidance` | convention | 2026-09-25 | Laying sod: brick pattern, cut edges, topsoil and compost under new sod, first watering, as published by four extension services |
| `sod-plugging-ifas` | convention | 2026-09-25 | Plugging a lawn from solid sod: spacing by species and square feet of sod per 1,000 square feet, UF/IFAS Table 3 |
| `soil-bag-observations` | market_survey | 2026-09-25 | Bagged garden soil sizes, a manufacturer's coverage statement, a contractor wheelbarrow's volume, and what ranking soil calculators assume |
| `soil-weights-and-sale-units` | standard | 2026-09-25 | Bulk soil and fill: loose and in-place weights per cubic yard, how bulk and bagged soil must be sold, and the vehicle payload label |
| `stock-lengths-us` | market_survey | 2026-09-09 | Board lengths actually sold at retail in the United States |
| `tile-joint-guidance` | convention | 2026-09-10 | Tile joint and offset guidance, attributed to published sources |
| `trim-nominal-actual-mdf` | market_survey | 2026-09-09 | Actual dimensions of primed MDF boards sold in the United States |
| `trim-waste-allowance` | convention | 2026-09-09 | Usual waste allowance on trim installed in lengths (running trim) |
| `wainscot-height-conventions` | convention | 2026-09-09 | Usual wainscoting height on an American interior wall |
| `wallpaper-roll-observations` | market_survey | 2026-09-10 | Wallpaper estimators and published roll formats, observed executions |
| `york-wallpaper-observations` | market_survey | 2026-09-10 | York Wallcoverings bolt chart, product roll formats, prices and the product-page calculator, observed |

3 records hold no constant: `deck-module-guidance`, `mosaic-sheet-planning`, `pool-band-planning`. They document that the
sources named give no universal value for the quantity, and that the figures the calculator starts
from are hypothetical examples.

2 records were read on a page that its publisher has since removed: their `source_url` is empty and
`source_status`, in the JSON record, says what was read, when, and what remains online.

## Scope and limits

United States, residential home improvement only. This is a register of published values, not original
research: values are what the named source stated on the verification date; product lines, prices and web
tools change. Nothing here is an installation
standard unless its status is `standard`, and nothing replaces a manufacturer's instructions.

## License and attribution

Released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), within this limit: CC BY 4.0 covers Calculiva's own contribution only: the compilation, its structure, the statuses, the scopes and the notes. Third-party values (published charts, list prices, product dimensions, tool outputs) are attributed to their sources and dated; no right over them is granted or claimed. Third-party text is not reproduced: each record names the page it was read on, and the excerpts read stay in Calculiva's working files. Calculiva is not affiliated with any company named.

Cite as: Calculiva, *Calculiva home improvement constants register*, version 2026-10-01, https://calculiva.com/data-sources/
