# Labs

# TODOs
- [ ] Assign Students to Lab Sections
  - [ ] Course staff should be able to create a form specifying the different lab sections with their times
  - [ ] Assign Students to Lab Sections using some sort of algorithm, initial guess is Ford-Fulkerson to maximize flow, however, this does not take into   account ranked preferences (would have to phrase question as what times *can* you make, rather than what times do you *prefer*)
  - [ ] Have some system of selecting dates for when labs are and are not, updatable
  - [ ] Accomodate Student Blocklist
- [ ] Take and Record Lab Attendence/Checkoffs
  - [ ] Lab TAs should have the option to either enter a student's CS login to check them off or manually check a box for the student
  - [ ] Should be able to have the option to checkoff students for individual checkpoints or to simply check them off for attending the lab
  - [ ] For just attendence based checkoffs, have a system to simply automate the attendence without being able to share a code of some sort so students must be present for the lab
  - [ ] Request lab checkoff/question
- [ ] Handle Temporary and Permanent Lab Swaps
  - [ ] Students have a form to be able to switch out of their lab section if there are slots available (have course staff able to override this limit if need be)
  - [ ] Have the option to require that a lab swap occurs x hours prior to a given lab section + they haven't already missed their section for that week
- [ ] Generate a Google Calendar
  - [ ] Automatically generate and populate a Google calender with the lab sections + send invites (private) to students for their lab section.
  - [ ] If a swap occurs the invite to that student should be updated to reflect the swap
  
# Tech Stack
- Fullstack TypeScript App based on NEXT.js hosted on Vercel?
- PostgreSQL? database interfaced using Prisma hosted on ???
- Typesafe API interface using tRPC
- Google OAuth via NextAuth
- Components and Styling via Material UI and Tailwind
