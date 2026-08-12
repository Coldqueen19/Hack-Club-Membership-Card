# Hack Club Membership Card
<img width="632" height="416" alt="image" src="https://github.com/user-attachments/assets/83497d7e-2341-4531-ad15-c05f05afdec3" />
This *Hack Club* membership card looks like a normal membership card, but has a twist! It has all the regualar stuff you'd expect to find on a membership card, like name and organisation. But there's more! It also displays a QR code, which links directly to my GitHub homepage. There is also a program from a 1964 book about programming techniques, as well as a cryptic explanation of the program, which intentionally gives no answer to the question "What does the program below do?" instead explaining what the program is. But the true gem here is the NFC functionality. An antenna is labelled with the words "TAP HERE to recieve contact info and to save into contacts" which clearly explain exactly how to use card. I plan for it to share Slack, Github, Hackclub and any other details I think should be included. I created this card because I think that it is cool to be able to share 5+ methods of communicating with me at just a single tap as well as some information on my specialisms and preferences. The idea is that I or someone else can tap this card to their phone and be able to access contact info quickly and easily at a hackathon or similar.
## Front Design
<img width="632" height="416" alt="image" src="https://github.com/user-attachments/assets/83497d7e-2341-4531-ad15-c05f05afdec3" />
I styled the front of the card on a regualar membership card you might get from any society but added my own twists like the QR code to my GitHub and the punch card program. I also made sure to be clear where the antenna was so as to to avoid confusion when tapping.
## Back Design
<img width="580" height="363" alt="image" src="https://github.com/user-attachments/assets/32f03dc9-3494-419d-867f-58fd5742a608" />
I decided that the back of my membership card didn't need to be compicated, so I opted for the simple Hack Club logo. I took the design from an abandoned project of mine, which had it almost exactly how I wanted it to be laid out and made a couple of adjustments.
## PCB
This is my PCB which I designed in EasyEDA STD
<img width="415" height="429" alt="image" src="https://github.com/user-attachments/assets/43793cc3-f326-4c19-a444-f7c482c778c7" />
<img width="529" height="350" alt="image" src="https://github.com/user-attachments/assets/b19023d9-e709-4ba2-a466-8ee581b15b24" />
## BOM
This should be everything you need to make this project yourself:
1x NT3H2111W0FHKH NFC Chip
1x ~2V LED
1x 47Ω resistor
1x 220nF capacitor
Additionally when creating the schematic, you will need to find a 25X48MM_NFC_ANTENNA for this project to actually work.
