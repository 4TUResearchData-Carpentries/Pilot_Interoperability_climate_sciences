# **Pilot feedback summary – Interoperability in Climate and Atmospheric Sciences**

22 October 2026, TU Delft Library, 09:30–16:30. 5 participants: 3 Civil Engineering PhD students (TUD), 1 software steward (UT), 1 observer. Tags: **P** \= participants, **O** \= observer, **(both)** \= raised by both.

We pilot the whole lesson, all (7) episodes , we built the feedback based on the observer and participants sticky notes open point up and down

## **1\. What worked well**

* Hands-on exercises and the lecture \+ exercise structure (P)  
* True/False and the compliance checker (P, O)  
* Pacing, breaks, interaction, helpers checking in (P)  
* Easy setup and installation (P); only the Windows `mkdir ~/` commands failed (O)  
* Aleks's summary linking the parts, and announcing what each live coding would show (O)  
* Content seen as valuable beyond this domain (P)

*Your comments:*

## **2\. What did not work as well**

* **Slides:** too much text, too small, light colours, long takeaways (both)  
* **Day length and pace:** too long to focus; talking could be faster (both)  
* **Intro:** too long and passive, duplicate definitions, jargon (both)  
* **API part:** hard to place, weak link to DAP/NetCDF (both)  
* **AI part:** better integrated into other parts (both)  
* **True/False:** ambiguous statements (e.g. "status"); only the semantic one gave feedback (both)  
* **Technical:** Zarr/Kerchunk exercise error (`>i4` dtype) for some; room screen cropped (O)  
* **Logistics:** agenda not sent beforehand; charger far from tables (P)

*Your comments:*

## **3\. Time estimates vs. actual**

The day ended about 15 minutes early. Observer: "We were not far behind after all\!"

| Episode | Planned (min) | Actual (min) |
| ----- | ----- | ----- |
| Intro | 30 | 22 |
| Structural | 30 | 32 |
| Semantic | 60 | 42 |
| DAP | 60 | 60 |
| API | 60 | 55 |
| Cloud-native | 30 | 52 |
| AI era | 15 | 18 |
| Lunch | 60 | 38 |

* Biggest exercises: DAP 39 min, Kerchunk demo 38 min, API exercises 20 \+ 23 min  
* Cloud-native overran by about 22 min; semantic and lunch ran short  
* The afternoon break seems to have been moved to after cloud-native  
* Intro start (09:45 planned vs 10:06 restart) and intro exercise times were not recorded

*Your comments:*

## **4\. Perceived difficulty**

* Prior knowledge varied: NetCDF/structural was hardest for one newcomer, common knowledge for another (both)  
* xarray slicing felt like too much time for a prerequisite (P)  
* Wanted more NetCDF background and more Zarr practice (P, O)  
* DAP image slides too dense (O)  
* No direct difficulty ratings were collected

*Your comments:*

## **5\. What to do differently next time**

* Define the target audience and set the prerequisites accordingly (both)  
* Send the agenda in advance (P)  
* Less talking, more hands-on; add a self-practice step after live coding (P, O)  
* Check the room setup and the Windows/Zarr exercises beforehand (O)  
* Add one slide on 4TU.ResearchData (O)

*Your comments:*

## **6\. What to change in the material**

* **Prerequisites:** make NetCDF/xarray explicit, or add a short NetCDF intro (both)  
* **Intro:** shorten, remove duplicate definitions, simplify jargon, "open standard format" → "open file format" (both)  
* **Structural/semantic:** define CF before mentioning it; merge repetitive slides; more on CF in a real file; add a CF-conformance exercise (P, O)  
* **DAP:** reveal image slides step by step; keep DAP vs OPeNDAP short; shorten takeaways (O)  
* **API:** rethink placement, replace the "workflow" slide with a list of API uses, consider using the OPeNDAP server instead (both)  
* **Cloud-native:** more Zarr practice, shorter takeaways, fix the Kerchunk error, add chunk-size guidance (P, O)  
* **AI era:** integrate into other parts (both)  
* **True/False:** rewrite ambiguous statements; give feedback consistently (both)  
* **Slides:** less text, larger font, better contrast (both)   
* **Setup:** fix the Windows `mkdir`/`cd` commands (O)

