+++
layout = "hanten"
published = "1258-25-22"
+++

# Jupiter
Assets for next_portfolio repo (Demo)


```js title="example.js"
console.log("Hello World");
```

# GFM

## Autolink literals

www.example.com, https://example.com, and contact@example.com.

## Footnote

A note[^1]

[^1]: Big note.

## Strikethrough

~one~ or ~~two~~ tildes.

## Table

| a | b  |  c |  d  |
| - | :- | -: | :-: |

## Tasklist

* [ ] to do
* [x] done

# remarkjs/remark-github
Some references:

*   Commit: f8083175fe890cbf14f41d0a06e7aa35d4989587
*   Commit (fork): foo@f8083175fe890cbf14f41d0a06e7aa35d4989587
*   Commit (repo): remarkjs/remark@e1aa9f6c02de18b9459b7d269712bcb50183ce89
*   Issue or PR (`#`): #1
*   Issue or PR (`GH-`): GH-1
*   Issue or PR (fork): foo#1
*   Issue or PR (project): remarkjs/remark#1
*   Mention: @extinctCoder

Some links:

*   Commit: <https://github.com/remarkjs/remark/commit/e1aa9f6c02de18b9459b7d269712bcb50183ce89>
*   Commit comment: <https://github.com/remarkjs/remark/commit/ac63bc3abacf14cf08ca5e2d8f1f8e88a7b9015c#commitcomment-16372693>
*   Issue or PR: <https://github.com/remarkjs/remark/issues/182>
*   Issue or PR comment: <https://github.com/remarkjs/remark-github/issues/3#issue-151160339>
*   Mention: <https://github.com/ben-eb>

















<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>


| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |


```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```


Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

This sentence uses `$` delimiters to show math inline:  $\sqrt{3x-1}+(1+x)^2$

This sentence uses $\` and \`$ delimiters to show math inline:  $`\sqrt{3x-1}+(1+x)^2`$

**The Cauchy-Schwarz Inequality**

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```

This expression uses `\$` to display a dollar sign: $`\sqrt{\$4}`$

To split <span>$</span>100 in half, we calculate $100/2$




Reference type	Raw reference	Short link
Issue or pull request URL	https://github.com/jlord/sheetsee.js/issues/26	#26
# and issue or pull request number	#1	#1
GH- and issue or pull request number	GH-1	GH-1
Username/Repository# and issue or pull request number	extinctCoder/portfolio_assets#26	extinctCoder/portfolio_assets#21
Organization_name/Repository# and issue or pull request number	github-linguist/linguist#4039	github-linguist/linguist#4039
If you reference an issue, pull request, or discussion in a list, the reference will unfurl to show the title and state instead. For more information about task lists, see "About task lists."


- [x] #1
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:



















































































this is image section
![alt text](image_one.webp "Title")
end image


<div id="webaddress">
<a href="isaac@applesdofall.org">isaac@applesdofall.org</a>
| <a href="http://en.wikipedia.org/wiki/Isaac_Newton">My wikipedia page</a>
</div>


## Qui arreptamque neque contigit in currus pellis

Lorem markdownum inponit erectos lugenti cervice: magis obstabat, ne
[iubet](http://www.ante.io/et-sacra.php). Ponto adit Nec, nataeque triplex virgo
meliore candentia, dubitare, per et carmine potest tori sagitta; iussit. *Quem*
una saepe Atlas vivunt *utrique iuveni*, ignescere in facunde sed praecinctus
**audeat nabat** fuerant, inane. Ferrumque corpore repetito pellite tempus,
inrita; spoliare in nisi.

- Nulloque violentam tendite ad et Abantiades tamen
- Petit imo tamen pinguia habendus
- Precor rebus naufragus protervis in genae per

## Nomina veneratur Delius

Illius dabat aut satiata postquam est, medentum depulerat amplectitur vario
nullo genetrix. Ab flavae ramosam telisque nocendi laevaque festum crimina age
pavit?

Et dedere pennas aliquid, a suumque, Elide ita, rogat. Modum diesque orbis
rursus. Uno tenet accedere totaque ablatum vestras exspatiata tamen est ossibus
quoque, est fuit facit in!

## Pertimuitque deum pectora fluunt

Erat illius simili, resides Erectheus reliquit, qua cur nigra in meliore
prosiluit amores. *Vim* arabat inrorant Telamon: hausitque quoque, exuit nec
quidem undis, sed. Tale futuros, ab Circen, di non pectoribusque rite: est?
**Meae o sine** fuit gens formatus est atlas victa!

    nvramDirectxGigahertz += -2;
    if (wave_ad_bit) {
        formulaGigaflopsIntelligence *= downInterfaceBandwidth;
        errorCd *= 5 - moodle_offline(mbpsAddress);
    }
    if (batch_state.column(rup_tag, 2)) {
        rosettaLionSoftware.server = ibm * ram - x_web;
    }
    if (ide + 223443) {
        regularSchemaSo += 4 + 2;
    } else {
        spool_web_service(duplexHandle, macintosh);
        rosetta_honeypot_analog /= ctrLinkedinWordart(-4) + drive;
        dsl(4, master_mask + software);
    }
    interpreterTerminalCmos.bankruptcyCamera(componentAddress);

## Spectatae forsitan diffusa mortisque Palaemona poteremur morte

Nec ausus pater dixi passim carpserat relinquam avem discedite non vestigatque
nova letalibus primum. Tumidaeque *anni limite palmis*, flammae multa Hector,
solum vocem? Iuvencae visus. Pignoribus terga, vox non porrigeret ferit gaudet
natos *silva permulcetque* faciet et vinci
[sinusque](http://iactat-minax.com/haustus-hic) auras ignobilitate populi
consurgere. Vultus nec dextra Silenum cetera exstinguere **dixit sanguine**:
pro, sub est porrigit illo **extimuit animo**; exitus!

O pectore nuper his plantis hic, quod tanti neget. Ego uritur ne sentire
**omen**. Tibi Romana, in animo Hersilie parvis nefandis nudare quondam?


## Currently

Standing on the shoulders of giants

### Specialized in

Laws of motion, gravitation, minting coins, disliking [Robert Hooke](http://en.wikipedia.org/wiki/Robert_Hooke)


### Research interests

Cooling, power series, optics, alchemy, planetary motions, apples.


## Education

`1654-1660`
__The King's School, Grantham.__

`June 1661 - now`
__Trinity College, Cambridge__

- Sizar

`1667 - death`
__Trinity College, Cambridge__

- Fellow



## Awards

`2012`
President, *Royal Society*, London, UK

Associate, *French Academy of Science*, Paris, France



## Publications

<!-- A list is also available [online](http://scholar.google.co.uk/citations?user=LTOTl0YAAAAJ) -->

### Journals

`1669`
Newton Sir I, De analysi per æquationes numero terminorum infinitas. 

`1669`
Lectiones opticæ.

etc. etc. etc.

### Patents

`2012`
Infinitesimal calculus for solutions to physics problems, [SMBC](http://www.techdirt.com/articles/20121011/09312820678/if-patents-had-been-around-time-newton.shtml) patent 001


## Occupation

`1600`
__Royal Mint__, London

- Warden
- Minted coins

`1600`
__Lucasian professor of Mathematics__, Cambridge University



<!-- ### Footer

Last updated: May 2013 -->

