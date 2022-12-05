# Share Class Notes 

# F.2

## Screencast: Updated December 4

Link: https://shareclassnotes.netlify.app
GitHub: https://github.com/rosemata/ShareClassNotes

## Functionality
 - [ ] Add notes by typing to textfield
 - [ ] Allows users to upload image (.jpg, .jpeg, .png, etc.) and will be converted to text
 - [ ] Edit/delete existing notes
 - [ ] View all notes without signing in
 - [ ] Search keyword from notes uploaded
 - [ ] Notes are clickable to see full text
 - [ ] Users can see list of notes they uploaded
 - [ ] Users can see date of when notes are uploaded
 - [ ] Unregistered users cannot see/upload documents.

https://user-images.githubusercontent.com/93716153/205525276-3c5da7fc-fb35-4ba1-9cdd-3f3f26231c03.mov

# F.2

## Include a description of what your app currently does
- allow users to search for key word
  - type "." to show all notes, or specific keyword
- allow users to sign in and upload their own notes to be added in our database

## Include a link to the deployment of your app in README.md - this can be your main app URL, or a branch deploy.
- https://github.com/rosemata/484_p1/tree/ming-branch
- https://shareclassnotes.netlify.app

## Optional but helpful - include a screencast that shows your current functionality in action. I should be able to run the app myself when I visit it though.



https://user-images.githubusercontent.com/93716153/202834044-f68cbab7-dee9-4576-a42a-af06c1fec7a0.mov



# F.1

## Set up CI to host the built version of your team GH repository. 
 - https://shareclassnotes.netlify.app
 - https://github.com/rosemata/484_p1

## Include a diagram (in text or drawn or however you please) of your tech stack:

 - Front end: React
   
 - Back end: Supabase
   
 - API: Algolia (search functionality), Cloud Vision API (picture to text)


<img width="814" alt="Screen Shot 2022-11-07 at 11 26 10 PM" src="https://user-images.githubusercontent.com/93716153/200482418-82b59c7d-7eac-4a3c-9832-6964f28f76ab.png">


<img width="815" alt="Screen Shot 2022-11-07 at 11 26 24 PM" src="https://user-images.githubusercontent.com/93716153/200482435-06977950-159c-4bd5-a0f5-2c80963c7113.png">


<img width="809" alt="Screen Shot 2022-11-07 at 11 26 35 PM" src="https://user-images.githubusercontent.com/93716153/200482444-57e0bf32-b5a6-4632-ab52-c08ecd020e5d.png">


<img width="817" alt="Screen Shot 2022-11-07 at 11 26 46 PM" src="https://user-images.githubusercontent.com/93716153/200482457-57c55243-2720-4dcc-a60c-bf4c5538532b.png">


<img width="814" alt="Screen Shot 2022-11-07 at 11 26 58 PM" src="https://user-images.githubusercontent.com/93716153/200482465-3a731b07-10ee-445a-8912-ea037cd4c858.png">


<img width="806" alt="Screen Shot 2022-11-07 at 11 27 09 PM" src="https://user-images.githubusercontent.com/93716153/200482473-17ca7880-8b69-4608-9ae2-ef7e992ca0ba.png">

## Include a short textual description of what MVP (minimum viable product) you will be aiming to complete by the end of week 13.
 - By week 13. User will be able to input their text notes and add it in our database

 - When user search a keyword. Notes with that keywords will come up as results

## What does your application do?  

- Writing notes during lectures is a real challenge! Make studying easier by uploading your notes and by having access to other student's notes in your class! Note Sharing App connects you to students in your class and from other Univesities.

## What makes it different than a CRUD app? I.e., what functionality does it provide that is not just a user interface layer on top of a database of user information, and the ability to view / add to / change that information?

- Allows users to view/upload different types of documents from .pdf, .docx, .jpeg, or image from camera.
- Search keywords from notes, even handwritted notes!

## What security and privacy concerns do you expect you (as developers) or your users to have with this application?
- User has the option to anonymously upload notes.
- Unregistered users cannot see/upload documents.
- Cannot inject malicious code into db.
