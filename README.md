# flatdango
## Description
- This challenge is working on  building out an application, Flatdango, that allows a user to purchase movie tickets from the theater.

## Requirements
- You need the following requirements:
1. A computer has Chrome installed.
2. Visual Studio Code installed or a text editor of your choice.
3. Node version 10 or higher installed.
4. A git hub account.

## Installation
### Option 1
1. Open the terminal on your computer (ctrl + shift + t).

2. Create a directory in your terminal named flatdango.
            
            use - mkdir flatdango

3. Clone the repository:
            
            use - git clone git@github.com:TracyAntonia/flatdango.git

4. Once it is done, change the directory to the repository folder:

            use - cd flatdango

5. Open it using VS code `Visual Studio Code`.

            use  - code .

6. Once you open your VS code, on your left-hand side on the explorer you will find the html, css, json and javascript files.

7. Open the HTML file and right-click on the editor and click on Open with Live Server.

8. The page should open in your Chrome browser.

### Option 2
1. You can fork this repository in your own account by clicking on `Fork` on this page.

2. Start the process in `OPTION ONE` above.
  
       NB: While cloning the repository, use your git hub link by clicking on code and copying the ssh key link.

## How it works
1. First you need to run `npx json-server --watch db.json` to run the json surver that has all the animals information.
2. After the server runs you should be able to view the page in your Chrome browser and vote for the animals.

## Summary
- As a user, you can:
   See the first movie's details, including its poster, title, runtime,
   showtime, and available tickets when the page loads. The number of
   available tickets are derived by subtracting the number of
   `tickets_sold` from the theater's `capacity`. A GET
   request is used to retrieve the film data.

  
