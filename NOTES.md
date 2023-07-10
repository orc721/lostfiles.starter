# Quick Notes on 404 Lost Files (Portrait) 



see inscribe here <https://ordinals.com/content/954f20424d6d66179f0e357264adbbdacd40fa00f4f15dd703cb4b46b6474fd9i0>


``` js
//	Collection: 404 Lost Files
//	Author: Inscriptor.unisat
//	Ticker: GRC-img

const data = {
	"sprite_xy": [24, 24],
	"pixelArt": true,
	"types": ["Portrait", "Landscape"],
	"layers": {
		"Portrait": {
			"traits": ["Base", "Arms", "Mouth", "Hat", "Eyes"],
			"Base": {
				"spriteSheet": "a3fb4ad6ed9654f236a2cb82a101022937c4aecabee4e6b3485e4f0fe26cd855i0",
				"traits": ["Blue 1", "Blue 2", "Blue 3", "Blue 4", "Green 1", "Green 2", "Green 3", "Green 4", "Violet 1", "Violet 2", "Violet 3", "Violet 4", "Orange 1", "Orange 2", "Orange 3", "Orange 4"]
			},
			"Arms": {
				"spriteSheet": "51462e54abfc85be2f813b275ee7ae71f787a771dd14cdd7cf1bf351fa0aa98bi0",
				"traits": ["Down 1", "Wave 1", "Wave 2", "Up 1", "Down 2", "Wave 2", "Wave 3", "Up 2", "Funky 1", "Funky 2", "Flex 1", "Flex 2", "Stop", "Hello 1", "Hello 2", "Welcome"]
			},
			"Mouth": {
				"spriteSheet": "1f2fa0155e47da349d964c79561db50af509ae2ce3fc7ee398fab904cba4cca5i0",
				"traits": ["Indifferent", "Happy 1", "Happy 2", "Happy 3", "Sad 1", "Sad 2", "Sad 3", "Sick", "Kawaii", "Kawaiiii", "Weird 1", "Weird 2", "Dog", "Cat", "Open", "Excited"]
			},
			"Hat": {
				"spriteSheet": "edb39fd1f0f33b9e989fa32a5a9a2962f806f4cd487f7e30f700014f13ed19aci0",
				"traits": ["none", "Party hat", "Flower", "Bandana", "Knitted Cap", "BKing Cap", "McD Cap 1", "McD Cap 2", "Cap", "Red cap", "Violet cap", "Do-rag", "Hat 1", "Hat 2", "Cowboy Hat 1", "Cowboy Hat 1"]
			},
			"Eyes": {
				"spriteSheet": "1199a91694b810b8d65270d5826262240d998ef5e295358e919318bd8e65f016i0",
				"traits": ["Shut", "Normal", "Big 1", "Big 2", "Big 3", "Big 4", "Angry", "Shut", "Kawaii", "Huge", "Aviator", "Disguise", "Nerdy", "Shades", "Deal-with-it", "Love"]
			}
		},
		"Landscape": {
			"traits": ["Base", "Arms", "Mouth", "Hat", "Eyes"],
			"Base": {
				"spriteSheet": "9a6102d0bd9d51166813ff6b71c27af45c802fa9033e6a9cd003b8eaa9beb7edi0",
				"traits": ["Blue 1", "Blue 2", "Blue 3", "Blue 4", "Green 1", "Green 2", "Green 3", "Green 4", "Violet 1", "Violet 2", "Violet 3", "Violet 4", "Orange 1", "Orange 2", "Orange 3", "Orange 4"]
			},
			"Arms": {
				"spriteSheet": "25a433592d30fc6a9da9afd7c9d36e39ae40d99662c206a81636d1e08bfe5c6fi0",
				"traits": ["Down 1", "Wave 1", "Wave 2", "Up 1", "Down 2", "Wave 2", "Wave 3", "Up 2", "Funky 1", "Funky 2", "Flex 1", "Flex 2", "Stop", "Hello 1", "Hello 2", "Welcome"]
			},
			"Mouth": {
				"spriteSheet": "38b48b0129eeaeaaba6c8afd21d447bbd1f5a4e0cae28eb8786b082da1ce1911i0",
				"traits": ["Indifferent", "Happy 1", "Happy 2", "Happy 3", "Sad 1", "Sad 2", "Sad 3", "Sick", "Kawaii", "Kawaiiii", "Weird 1", "Weird 2", "Dog", "Cat", "Open", "Excited"]
			},
			"Hat": {
				"spriteSheet": "92d82a111a00aa1f30f1d8159dc71c709b5dc34821e10c92b47987940051307ci0",
				"traits": ["none", "Party hat", "Flower", "Bandana", "Knitted Cap", "BKing Cap", "McD Cap 1", "McD Cap 2", "Cap", "Red cap", "Violet cap", "Do-rag", "Hat 1", "Hat 2", "Cowboy Hat 1", "Cowboy Hat 1"]
			},
			"Eyes": {
				"spriteSheet": "f09575714604582f979828fb3ee4999610ac8ed55158284aea6da7746a00d35ei0",
				"traits": ["Shut", "Normal", "Big 1", "Big 2", "Big 3", "Big 4", "Angry", "Shut", "Kawaii", "Huge", "Aviator", "Disguise", "Nerdy", "Shades", "Deal-with-it", "Love"]
			}
		}
	}
}
```





from phunks discord:


TheInscriptor writes:

Cat is out of the hat!

Twitter how-to thread:
<https://twitter.com/TheInscriptor/status/1675973973266268165>

On-chain NFT editor:
<https://ordinals.com/content/04eb8764b05a42ac8a1784bd3f862ae749cf0a8eec5909f5e5d1ae18c9e5c0a7i0>

Recommended (and cheapest) inscription tool:
https://looksordinal.com/

Some examples:
- <https://magiceden.io/ordinals/wallet?walletAddress=bc1ppkxk4ppjn238j89emdskv873trvfwpgc850xxamufz58w7k0j4mq3stpkq>
- <https://ordinalswallet.com/address/bc1ppkxk4ppjn238j89emdskv873trvfwpgc850xxamufz58w7k0j4mq3stpkq>

Whats next? More Phunks?

o o o

There are currently 3 recursive "techs" under development (AFAIK)

GRC-img
- Uses sprite sheets as layers plus full trait data, all rendered as HTML. 
- I still have a lot to  improve on compatibility and token size front

BitGen
- Uses single images per trait, all rendered as SVG, probably most advanced one
https://twitter.com/BobBodily/status/1671742076386684929

G-BRC-721 or 69
- I don't know, looks like they are taking inspiration from BitGen 
https://twitter.com/RAF_BTC/status/1674798019273969665


geraldb writes:

if i may add ordgen / ORC-721 is recursive too - was even recursive before ord v0.6 itself ;-). see https://github.com/ordbase/generative-orc-721 
all generative layers "on-chain" ... if people want an "on-chain" image you can inscribe (recursive) .SVG. 
.. or "plain" .PNG.  generative! your numbers, your image! is the ordgen / ORC-721 tagline.

anyways - i think the standout world's 1st & unique feature of GRC is the "on-chain" designer / editor ... 
... not really a fan of inscribing "static" generative images in .HTML frames with lots of javascript machinery  (i'd say "static" .SVG without any scripts would be a way better choice - .SVG is an image (format) by definition and works "on-chain" and recursive in ord v0.6.1+ now).

here's an idea - to compare ordgen / ORC-721 with GRC let's do a deploy of 404 Lost Files (Portrait) - only one text inscribe needed to start free mint (first-come / first-serve).
here's the  layer definition inscribe in GRC -> https://ordinals.com/content/954f20424d6d66179f0e357264adbbdacd40fa00f4f15dd703cb4b46b6474fd9i0
now compare with - yes, that's all - the deploy text for ordgen / ORC-721.
note: the deploy only includes the 5 portrait spritesheets (base,  arms,  mouth,  hat,  eyes) ... if you want to add the landscape too, please tell. otherwise let's do portrait only. here we go:

```
og deploy lostfiles
name: Lost Files (Portrait)
max: 404
dim: 24x24
a3fb4ad6ed9654f236a2cb82a101022937c4aecabee4e6b3485e4f0fe26cd855i0
51462e54abfc85be2f813b275ee7ae71f787a771dd14cdd7cf1bf351fa0aa98bi0
1f2fa0155e47da349d964c79561db50af509ae2ce3fc7ee398fab904cba4cca5i0
edb39fd1f0f33b9e989fa32a5a9a2962f806f4cd487f7e30f700014f13ed19aci0
1199a91694b810b8d65270d5826262240d998ef5e295358e919318bd8e65f016i0
```

... now if anyone inscribes this deploy text - the previewer to help along with the free mint (first-come/first-serve) is ready here -> https://ordbase.github.io/generative-orc-721/lostfiles    wen deploy?


Q: so we save bytes with ordgen / orc-721?

A: yes. always saving bytes (and sats!)
in ordgen / ORC-721 a mint inscribe text is about 100 bytes only e.g.

     og mint lostfiles 15 21 37 54 64

 ... in GRC it is about 10x min. (>1000 bytes)



```` html
<head>
  <title>404 Lost Files</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="token" content="GRC-img">
  <meta name="slug" content="404-lost-files">
  <script src="/content/524315b5b9ea64f277408237e92c7a6d9767ced60eb751651853324e43f91ea4i0"></script>  <!-- collection meta inscribe -->
  <script src="/content/954f20424d6d66179f0e357264adbbdacd40fa00f4f15dd703cb4b46b6474fd9i0"></script>  <!-- collection data/generatives inscribe -->
  <script src="/content/662bed94d3ce10202813150df420a08f0fa5566da2d2adc7091d26c2992805b1i0"></script>  <!-- token/html generation script -->
  <link rel="stylesheet" href="/content/0959deb05b19aba244fe1fe001b7ce3d58ac7c09e5e3f2c274d66dc2846eaa65i0">
</head>

<body onload="token_load()" id="content" data-dna="000a0a0e030c" data-metadata="true">
  <div class="container"><canvas id="canvas_content" class="content" width="24" height="24"></canvas><button onclick="token_showInfo()" id="showInfo" type="button" class="info" hidden="">i</button>
    <div id="name" class="name" hidden=""></div>
    <div id="error" class="error" hidden=""></div>
    <div id="traits" class="traits" hidden=""></div>
  </div>
</body>
```` 


collection inscribe:
<https://ordinals.com/inscription/524315b5b9ea64f277408237e92c7a6d9767ced60eb751651853324e43f91ea4i0>


``` js
const collection = {
	"token": "GRC-img",
	"slug": "404-lost-files",
	"name": "404 Lost Files",
	"description": "Important Files Lost during FTX collapse. Rediscovered as Generative Recursive Collection utilizing the GRC-img contract",
	"author": "Inscriptor.unisat",
	"dataID": "954f20424d6d66179f0e357264adbbdacd40fa00f4f15dd703cb4b46b6474fd9i0",
	"contractID": "662bed94d3ce10202813150df420a08f0fa5566da2d2adc7091d26c2992805b1i0",
	"styleSheetID": "0959deb05b19aba244fe1fe001b7ce3d58ac7c09e5e3f2c274d66dc2846eaa65i0",
	"showMetadata": true,
	"localTest": false,
	"supply": 404
}
```

token / html generation script:
<https://ordinals.com/inscription/662bed94d3ce10202813150df420a08f0fa5566da2d2adc7091d26c2992805b1i0> 


``` js
//    ____  ____    ____         _
//   / ___||  _ \  / ___|       (_) _ __ ___    __ _
//  | |  _ | |_) || |     _____ | || '_ ` _ \  / _` |
//  | |_| ||  _ < | |___ |_____|| || | | | | || (_| |
//   \____||_| \_\ \____|       |_||_| |_| |_| \__, |.v1
//  --------------------------------------------|___/---
//  Generative Recursive Collection token (v1)
//  Author: Inscriptor.unisat
//  Ticker: GRC-img

const spriteX = data.sprite_xy[0];
const spriteY = data.sprite_xy[1];

const tokenSpriteSheets = [];
const tokenTraitsMax = [];
const tokenTraits = [];

const typeNames = data.types;
var traitNames = [];

function loadData(typeName)
{
	traitNames = data.layers[typeName].traits;
	traitNames.forEach(function (traitName, i)
	{
		tokenSpriteSheets[i] = data.layers[typeName][traitName].spriteSheet;
		tokenTraitsMax[i] = data.layers[typeName][traitName].traits.length - 1;
		tokenTraits[i] = data.layers[typeName][traitName].traits;
	});
}

function token_load()
{
	let content = document.getElementById("content");
	let dna = hexToBytes(content.dataset.dna);
	let type = dna.shift();
	if (type >= typeNames.length)
	{
		token_error("Invalid Type");
		return;
	}

	loadData(typeNames[type]);
	if (dna.length != traitNames.length)
	{
		token_error("Invalid DNA");
		return;
	}

	document.title = collection.name;
	if (content.dataset.metadata)
	{
		let dnaTraits = [];
		dnaTraits.push("Type: " + typeNames[type]);
		traitNames.forEach(function (traitName, i)
		{
			if (dna[i] <= tokenTraitsMax[i])
			{
				dnaTraits.push(traitNames[i] + ": " + tokenTraits[i][dna[i]]);	
			}
			else
			{
				token_error("Wrong trait");
				return;
			}
		});
		document.getElementById("name").textContent = collection.name;
		document.getElementById("traits").textContent = dnaTraits.join(" | ");
		document.getElementById("showInfo").hidden = false;
	}
	drawSprites(tokenSpriteSheets, dna, "content");
}

function token_showInfo()
{
	if (document.getElementById("name").hidden == true)
	{
		document.getElementById("name").hidden = false;
		document.getElementById("traits").hidden = false;
	}
	else
	{
		document.getElementById("name").hidden = true;
		document.getElementById("traits").hidden = true;
	}
}

function token_error(text)
{
	document.getElementById("error").hidden = false;
	document.getElementById("error").textContent = text;
	console.log("Error: " + text);
}

function drawSprites(spriteSheetsIDs, dna, targetCanvas) 
{
	let loaded = 0;
	let spriteSheets = [];
	let canvas 	= document.getElementById("canvas_" + targetCanvas);
	let context = canvas.getContext('2d');
	context.clearRect(0, 0, canvas.width, canvas.height);
	context.imageSmoothingEnabled = !data.pixelArt;
	
	function drawImages()
	{
		spriteSheets.forEach(function (spriteSheet, i)
		{
			var maxX = spriteSheet.width;
			var maxY = spriteSheet.height;
			
			let posX = (spriteX * dna[i]) % maxX;
			let posY = spriteY * Math.floor(spriteX * dna[i] / maxX);

			posY = Math.min(Math.max(posY, 0), (maxY - spriteY));

			context.drawImage(spriteSheet, posX, posY, spriteX, spriteY, 0, 0, canvas.width, canvas.height);
		});
	}
	
	function onLoad()
	{
		if (++loaded == spriteSheets.length) 
		{
			drawImages();
		}
	}

	for (let i = 0; i < spriteSheetsIDs.length; i++)
	{
		let spriteSheet = new Image();
		spriteSheet.addEventListener("load", onLoad);
		spriteSheet.src = getUrl(spriteSheetsIDs[i]);
		spriteSheets[i] = spriteSheet;
    }
}

function drawSprite(spriteSheetID, pos, targetCanvas)	
{
	let canvas 	= document.getElementById("canvas_" + targetCanvas);
	let context = canvas.getContext('2d');
	
	context.clearRect(0, 0, canvas.width, canvas.height);
	context.imageSmoothingEnabled = !data.pixelArt;

	let spriteSheet = new Image();
	spriteSheet.onload = function ()
	{
		var maxX = spriteSheet.width;
		var maxY = spriteSheet.height;
		
		let posX = (spriteX * pos) % maxX;
		let posY = spriteY * Math.floor(spriteX * pos / maxX);

		posY = Math.min(Math.max(posY, 0), (maxY - spriteY));
		
		context.drawImage(this, posX, posY, spriteX, spriteY, 0, 0, canvas.width, canvas.height);
	};
	spriteSheet.src = getUrl(spriteSheetID);
}

function bytesToHex(bytes) 
{
	let hex = [];
	for (let i = 0; i < bytes.length; i++) 
	{
		let current = bytes[i] < 0 ? bytes[i] + 256 : bytes[i];
		hex.push((current >>> 4).toString(16));
		hex.push((current & 0xF).toString(16));
	}
	return hex.join("");
}

function hexToBytes(hex) 
{
	let bytes = [];
	for (let c = 0; c < hex.length; c += 2)
		bytes.push(parseInt(hex.substr(c, 2), 16));
	return bytes;
}

function getUrl(inscriptionID) 
{
	if (collection.localTest)
		return inscriptionID;
	else
		return "/content/" + inscriptionID;
}
```



### Q&A w/ The Inscritptor

critique on (Generative Recursive Collection) GRC-img v1  
(copy-n-pasted from ordinal punks discord chat)


The Inscritptor: Cat is out of the hat ...


Q: looks great.   may i ask what is the reason for the (GRC) mint token inscription to use .HTML with scripts and such - why prefer it over  let's say  a simple option in  .SVG with no-scripts (with the bonus that a .SVG inscribe is by definition an image - that you can use for future recursions?) 


The Inscritptor: It was best I could do

Q: happy to help with the .svg version v2 ;-).


The Inscritptor: That would be awesome. I will have to figure out how to crop layers and pass them to svg. BitGen guys are doing it by passing it as DataURL  
However token optimizations are next step.


Q: for svg the stacking order is simply the order of the images listed.
example:

```
<svg width="24px" height="24px" xmlns="http://www.w3.org/2000/svg%22%3E
  <image href="/content/7fbfed7e38bbcaf851c2c4426b4c4ede9d09b6e6fd87a040403852681c7c19c2i0" />
  <image href="/content/128d1e42f85e67d2a6b0c4c78e9ad47f7d66ed7699e77ddd0a4f0b8a21cdf736i0" />
  <image href="/content/62ec589582651e49ed722241dab3bdb93fbd8ddf3fab3d891a30165126dddbcfi0" />
  <image href="/content/b866e8f3f51c385a3ae27e65c5abe68e6086a6b74935b1b692de8587f5858148i0" />
</svg>
```

.. and it is xml (html-like) that is you can add your own attributes e.g. data-dna or data-trait or whatever.


The Inscriptor: I am using sprite sheets so I need to crop the layers. That is why I am drawing onto canvas
GRC-img so more code heavy because I am working with more data - layer combinations and names for each trait

If it was good design... time will tell. However what I can save on token size is to inject more html on the fly.


Q: I see.   i think in svg you can crop the (spritesheet) images too (but sure i need to research to find out - i cannot tell you now how but i am 100% sure it is possible without any "hacks".)
... and for the metadata you can add to `<svg ...>`


The Inscriptor: Yeah its possible to use some css cropping or canvas draw... with SVG I would have to tap in some js5 API to something to actually process the image 

Metadata are decoded on the fly from DNA and injected as text

Q: .. eg <svg data-dna="000007030601" data-metadata="true" data-name="404-lost-files" ...>

The Inscriptor: Oh as source, yeah



Q: 

> with SVG I would have to tap in some js5 API to something to actually process the image 

i am 100% sure you can do croping spritesheet image WITHOUT any js / script.   only css magic for px offset calculation.    ps:   anyway, i'd say the killer is that an svg document is an image by definition (and thus, can get used for more recursions). 


The Inscriptor: Hmm will have to look in to that. Thanks for tip!


Q: if i may ask a dumb question about GRC - why not inscribe the .PNG?  what is the point of the .HTML frame / token?  (the metadata? - that you can add inside the .PNG too) what am i missing?

... about the svg ... yeah the Bitgen idea of using inline dataurls for the image source looks like a winner - than the svg works "on-chain" and "off-chain" too and is a "stand-alone" / self-containted .svg image / document - can't be any simpler than that (other than inscribing the .PNG itself). 

note: it is daturls  (plural) - every attribute / trait / sprite / tile  in the svg is an image with an inline dataurl  (and yes, a svg with single inline image in base56 is pointless). 

Q: again don't get me wrong asking  questions here.  congrats to the 404 Files mint / launch. love it. great pixel art  - halleluja yes, not more punks but happy & sad 24px portrait and landscape characters ;-).  allow me one more question about GRC  (assuming it's not bespoke and one-off) - how can i get started on my own GRC collection - any "off-chain" documentation available about the "on-chain" GRC machinery? 


TheInscriptor: I will have to write one, but I will be off for two weeks so it will have to wait.

Also looks like I will have to work on optimizations a lot and also indexer. UniSat cant do text search in HTML inscription.
