## Inspiration

&emsp;&emsp;Inspired by Jane Goodall braved a realm of unknowns to give the world a remarkable window into humankind’s closest living relatives. Through nearly 60 years of groundbreaking work, Dr. Jane Goodall has not only shown us the urgent need to protect chimpanzees from extinction; she has also redefined species conservation to include the needs of local people and the environment. Today she travels the world, speaking about the threats facing chimpanzees and environmental crises, urging each of us to take action on behalf of all living things and planet we share.

&emsp;&emsp;In this project we are addressing about how paperless reduces impact on forests-tress, decreases the amount of waste. Go paperless,Save Trees, Save Earth,
## What it does

&emsp;&emsp;Raptorz Animal Rescue application is built for one who find companion by adopting dog,cat,bird which makes life fulfillment with love,care,protection also shelter and caring for animals.

###More in detail about application,

<li>**Client(Adopter):-**</li>
 &emsp;&emsp;Adopter who like to have a companion fills form via Animal Rescue App with all his/her relevant details which gets stored in sharepoint via powerflow.Once the data submitted powerflow triggers a flow which shares document for adoption a standard procedure via mail which configured passed through docusign api and oauth authorization connectivity.Document created through docusign template which shows and guide the adopter to fill the required mandatory fields, once data filled adopter Esign as a acceptance validation.

<li>**Organization Team:-**</li>
 &emsp;&emsp;Post submission by adopter document mail has been sent to admin of the Animal Rescue organization who check everything looks good or not, once validation completed and passed admin Esign the document.
&emsp;&emsp;Post validation document sent to Managing director who verify Adopter details is legit or no, after verification Managing director Esign the document.

<li>**New Companion:-**</li>
&emsp;&emsp;Eveything in place, now Adopter is verified legit citizen and authorized to adopt his/her companion.

## How we built it

###Involves 4 steps:-
Application is built using java,html,css3,and data stored in shared point.

<li>**webview:-**</li>
 &emsp;&emsp; Built using Html,css3,java,json,bootstrap..

<li>**Backend:-**</li>
 &emsp;&emsp;Once the form is submitted data stored in share point with help of powerflow.

<li>**Powerflow:-**</li>
 &emsp;&emsp;Send email communication to fill the doc to the Adopter who is seeking for companion via cloud trigger.Also store data into share point via forms.

<li>**Docusign:-**</li>
&emsp;&emsp;Docusign template has been created with required feilds along with receipt mandatory esignature for acceptance and receipt order of the envelope whom mail should be sent has been set orderwise.

<li>**Docusign Api call :-**</li>
&emsp;&emsp;My api key and account id has been added to the custom connector in powerflow for authorization and connection set.


## Accomplishments that we're proud of

&emsp;&emsp;Learnt about docusign Esign feature which helps organization go digitally a paperless friendly environment.

##  What's next 

&emsp;&emsp;Need to integrate to cosmodb and other azure resource.

MIT License

Copyright (c) 2022 TCC-TWILIGHTCLOUDCODERZ -Deepan,Kavya,Ramya-Team Raptor

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
