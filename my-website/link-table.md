| File           | Link text                | Destination                                      | Link type| Why it works                                                         |
| ---------------| -------------------------| ------------------------------------------------ | -------- |
| `index.html`   | Home                     | `index.html`                                     | Relative | Links to the homepage in the same folder.                            
| `index.html`   | About                    | `about.html`                                     | Relative | Links to the About page in the same folder.                         
| `index.html`   | Project                  | `project.html`                                   | Relative | Links to the Project page in the same folder.                        
| `index.html`   | Contact                  | `contact.html`                                   | Relative | Links to the Contact page in the same folder.                        
| `index.html`   | Services                 | `pages/services.html`                            | Relative | Enters the `pages` folder to open Services.                          
| `index.html`   | MDN Web Development      | `https://developer.mozilla.org/en-US/docs/Learn` | Absolute | Uses a complete URL to an external website.                          
| `index.html`   | Return to welcome section| `#welcome`                                       | Fragment | Jumps to the section with `id="welcome"` on the same page.           
| `about.html`   | Home                     | `index.html`                                     | Relative | Opens the homepage in the same folder.                               
| `about.html`   | About                    | `about.html`                                     | Relative | Links to the About page in the same folder.                          
| `about.html`   | Project                  | `project.html`                                   | Relative | Opens the Project page in the same folder.                           
| `about.html`   | Contact                  | `contact.html`                                   | Relative | Opens the Contact page in the same folder.                           
| `about.html`   | Services                 | `pages/services.html`                            | Relative | Enters the `pages` folder to open Services.                          
| `project.html` | Home                     | `index.html`                                     | Relative | Opens the homepage in the same folder.                               
| `project.html` | About                    | `about.html`                                     | Relative | Opens the About page in the same folder.                             
| `project.html` | Project                  | `project.html`                                   | Relative | Links to the Project page in the same folder.                        
| `project.html` | Contact                  | `contact.html`                                   | Relative | Opens the Contact page in the same folder.                           
| `project.html` | Services                 | `pages/services.html`                            | Relative | Enters the `pages` folder to open Services.                          
| `contact.html` | Home                     | `index.html`                                     | Relative | Opens the homepage in the same folder.                               
| `contact.html` | About                    | `about.html`                                     | Relative | Opens the About page in the same folder.                             
| `contact.html` | Project                  | `project.html`                                   | Relative | Opens the Project page in the same folder.                           
| `contact.html` | Contact                  | `contact.html`                                   | Relative | Links to the Contact page in the same folder.                        
| `contact.html` | Services                 | `pages/services.html`                            | Relative | Enters the `pages` folder to open Services.                          
| `contact.html` | Send an email            | `mailto:mahmudibrahim850@gmail.com`              | Email URI| Opens the user's default email application to compose an email.      
| `services.html | Home                     | `../index.html`                                  | Relative | Moves up one folder from `pages` to the root folder.                 
| `services.html | About                    | `../about.html`                                  | Relative | Moves up one folder to find the About page.                          
| `services.html`| Project                  | `../project.html`                                | Relative | Moves up one folder to find the Project page.                        
| `services.html`| Contact                  | `../contact.html`                                | Relative | Moves up one folder to find the Contact page.                        
| `services.html`| Services                 | `pages/services.html`                            | Relative — incorrect | Looks for `pages/pages/services.html`; it should be `services.html`.