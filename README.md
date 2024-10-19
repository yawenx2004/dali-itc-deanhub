# dali-itc-deanhub

hello!! this is an explanation of what we have on [figma here](https://www.figma.com/design/0TEFlXXxJIuh4MoLBIFV7e/DeanHub-24F?node-id=1764-970&t=H7F1VNQ5rhMY4SbT-1). couple of housekeeping notes—

- currently (as of 19 oct. 24) this is for mostly UX references only; the contents of the cards and the UI of the tabs/search bar for multi-student view are subject to change
- the four skeleton sections are constructed by pulling an instance of things from the **components** section onto the background; therefore if we edit anything inside the components section, all instances of the corresponding components change (think of this like objects from oop perhaps)

## overall layout
1. header
2. search bar for searching for student / tabs for multi-student navigation
3. basic information cards (overview & warning flags)
4. general/academic/advising/critical events pages (you select on a menu to display each one at a time)

## feature scope
This is in no specific order of importance.

1. **collapsible cards** form the basis of information architecture (i.e. the bulk of textual/graphical information is going to be displayed on the cards)
   - specifics of the content are very subject to change; for now just have them
   - each card needs a property that allows it to be visible to some administrators but not others, so that we could implement differing levels of access (e.g. some deans can view the card titled "emergency contacts," some cannot)
2. **search bar** — you type in a student's information and it is displayed
   - sticky
4. **multi-student view navigation** — akin to chrome tabs
   - you can click on the plus sign to add a new tab, and from there on search for a new student in that tab, without closing tabs for other students
5. **general, academics, advising, and critical events pages**
   - treat these as 4 sub-pages under the tabs navigation (i.e. that row that displays "general," "academics," etc.)
   - clicking on the tabs navigation allows you to switch between them
   - each page is, once again, displayed through a series of cards
6. **early warning system**
   - alerts displayed for "red flags"
   - you can click on a red flag to view more information & dismiss it
   - a toggle allows for viewing of dismissed flags
   - at time of typing this, i haven't really prototyped this on figma
7. **sign-out function** akin to darthub's

