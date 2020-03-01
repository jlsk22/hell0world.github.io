---
Disobedient Object's
---
Disobedient Objects was an exhibition, curated by Catherine Flood and Gavin Grindon, of tools of social change and designed 
objects created by grassroots social movements from around the world.

"There are many ways art and design practices can be politically active. But we aren’t primarily concerned with the 
institutional frames of the sometimes isolated gestures of either ‘critical design’ or even programmes of ‘interventionist’
participatory art. Likewise ‘activist-art’ and more recently ‘design activism’ are established terms referring respectively 
to a nebulously broad range of artists’ practices or to top-down socially responsible professional design. We do not wish to 
denigrate such practices, and it is true that there are many kinds of ‘activism’, but at the same time the broad use of the 
term ‘activism’ has also functioned as an enclosure of cultural value, authenticity and impact on the part of professional 
artists, critics, designers, corporations and even NGOs. Rather, it seems imperative to begin with the actually existing but 
often unacknowledged grassroots cultures of activist social movements in order to properly contextualize the many overlapping 
current debates on art, design and social change."

Disobedient Objects by Catherine Flood and Gavin Grindon, 2014

### Parameters: 
- Choose a TOPIC, a DEVICE, and a MOOD
- Make an INTERACTIVE Critical Object based on your selections
- The technology should be conspicuous ( I should not be able to see your Arduino board / Wires / Motors / ... )
- Your Device is your tool to connect with your audience (Sarcasm, Metaphor, Juxtaposition, Irony, Surrealism, ...)
- Most likely the Mood will help to setup the tone of the interaction

### Topic:
- The US Government sucks and change within the system must happen from the bottom --> up

### Device:
- Juxtaposition

### Mood:
- ANGRY

V is for Vendetta Mask as either stickers/stencils/stamp with barcodes and the app name, if you download the app and scan the barcode, it'll show you on a map everywhere the mask has been spotted and scanned in your area ---> pushing this ideal of 
unity and most likely utilized at the start of any movement gaining momentum. 

#### A. Research
I've researched many sites online to see the best/cheapest method for building my own mobile app with geo-location and barcode
scanning capabilities through reviews [like these](https://www.werockyourweb.com/mobile-app-builder/)

- React native
- [Appmakr](https://www.appmakr.com/)
- [Siberian CMS](https://apptooltester.com/reviews/siberian/#comments)
- [Appery.io](https://www.comparakeet.com/best-app-makers/appery-io-review/)
- Or build it myself using XR Code in AppleStore + [CodewithChris tutorials](https://www.youtube.com/watch?v=jniJeamcIUU)

I can pay someone to build it for me at:

- Upwork.com
- Fievrr.com
- Codementor.io

**Based on my research, I think I'm going to use React Native**

#### B. Implementation
- Build interface on [RN](https://reactnative.dev/docs/getting-started) (no profiles) 
- [Make own unique barcode/qr code](https://barcode.tec-it.com/en/MobileQRCode?data=This%20is%20a%20QR%20Code%20by%20TEC-IT%20for%20mobile%20applications)
- Add geo-navigation + [barcode scanners] (https://docs.scandit.com/5.8/react_native/react-native-integrate.html)
- Add markers on geo map based on location 
- Make physical stencil/stamp/sticker
- Test it

#### C. Result

<img src ="Vendetta.jpg" width = "400" height ="500" >

