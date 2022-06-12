## Week 1 Assignment: Flixster

Submitted by: **Annesa Tran**

Estimated time spent: **10** hours spent in total

Deployed Application (optional): [Flixster Deployed Site](ADD_LINK_HERE)

### Application Features

#### CORE FEATURES

- [x] User can view a list of current movies from The Movie Database API as a grid view
  - The grid element should have an id of `movies-grid`
  - Each movie wrapper element should have a class of `movie-card`
- [x] For each movie displayed, user can see the following details:
  - Title - the element should have a class of `movie-title`
  - Image - the `img` element should have a class of `movie-poster`
  - Votes - the element should have a class of `movie-votes`
- [x] User can load more current movies by clicking a button at the bottom of the list
  - The button should have an id of `load-more-movies-btn`.
  - When clicked, the page should not refresh.
  - New movies should simply be added to the bottom
- [x] Allow users to search for movies and display them in a grid view
  - There should be a search input element with an id of `search-input`
  - Users should be able to type into the input
  - When a user hits 'Enter', it should send a search request to the movies API
  - The results from the search should be displayed on the page
  - There should be a close icon with an id of `close-search-btn` that exits the search, clears results, and shows the current movies displayed previously
- [x] Website accounts for basic HTML/CSS accessibility features
- [x] Website should be responsive

#### STRETCH FEATURES

- [ ] Deploy website using GitHub Pages. 
- [x] Allow user to view more details about a movie within a popup.
- [x] Improve the user experience through CSS & animation.
- [ ] Allow movie video trailers to be played using [embedded YouTube](https://support.google.com/youtube/answer/171780?hl=en)

### Walkthrough Video

"Now Playing" movies appear in a grid and load more button works
![](https://previews.dropbox.com/p/thumb/ABguihS5YL-_lxFdrU2n-tT7fah2j5Y70i1Bqgn9Oso7lY3GL-rb9mAznfR7FzCOEuOQgBgw4mcr95Wffzqi9LCD7qmiRSIzwWqXl7dfW2lHOHH11vVpXrkotHQqWyReeGGOrcd8Aa4HNIywxjg9Wz302hVuGEGe5BYgcavQn9z_qlvFO-erYOch3y_Ts7jOD3bZjGjwboz_3xtn87cDoZaeAM8AydRT7-LYAJGdigtc10P_pGoLCauCpJgJEcYSF_kZSiaOR7VkOUFVwWu-oUBSysHrYylBJO2_IbfwuAHYQwnlrtgBeAHPl8UeFFR1oRrUNYp7ypOxHO9oIDp8ru_uLsbqZtgSJzbG6AaEf4NSjFsXxZ4egHD9AXQrplJiGsomBI3t8gDqGrRhyKj73XhSZgA-g8bA5SP1zC_wSt_8dwkSII7qNIHj2OXInN_QnExwLaEU2XYbjqkD70X6zyfv5lFIDz7kdyE7a9xVIlVhSkCb7gNfoPii2NLPmmWS7x02Y38zMKDK5ZhtMe2PcN3aZLZgw4QOilHL1OuZCh6ZgqEzLfkIbVp7HAA8unnWhss/p.gif)

Searching for movies and loading more
![](https://previews.dropbox.com/p/thumb/ABjFvsJ4i60MRCV2R7VydoNDZPM2XYuKtVcDoBUvPTlwPetoHACSFUWp_Eozk2n7Aj4vA5_x868jORE_9Bf_rco7lAz07hFhAVG8OazQOBH02DYo7x6H9WR8bhIIUyjn7e_KWJUrmNhZVlBT0lPL17PyYR0m6PPOd-gbdR5fNpUI8AHV6umteekpvFiijqMclvxpsl4Iq2HO102cM0kYutb5U98MdP_XjEyzNob5T5nX82anZKpkkNsEr4XcBcXDL3TDgMb-GL6sobkBShkkNYLoMbMTmP-NYQ_OJm70k8rk8Gz09EgKI0O41D7ysVwtyLGc4lwAyO3djJMR1BfVNZbvpeYCpwUJjIXW8IAog2ZigOmkdOfIaQ8t_QeSNhAAnb8T86qSgctz85tXNbM1rISMdDvslko6g0cMYhbE97eUjibztDXvpxDXqjEwumvlvX7t8xO1aV_FqyH0h6LU4TArWrhbhpdpYD0UHwlP0laKZjIRt4-fGn7l2MRm0lyv7U8/p.gif)

Clearing search to go back to Now Playing and Default image for movie cards appears
![](https://previews.dropbox.com/p/thumb/ABi-Z88YW0fRNDcDW6RB6rRCwZofbGPTVsj7FzIpjNGQJXoqRg7d2kU3LjxfdxmTnXQ8M5hvtNPzw4umrrf5oUi0iA7HXr5xki8O_S7zdTnuAquiW2TRnVEnsVBgrgv9eCRG3drDyDKwAWY77aK9FXRc6extHe-iJX040KZFFAwvfSw_DdZBU1SDwCzv-eSActKo-tm8qyU_JQkxaTOCT-sDeCojO32CIuvwmrT8eh4VNrKIyVHOQWqrddJIGt2gTR-hGD1zVrMBEWTybSlruXwsbWDTbBicpnnq_9pOgZT38kOnI-l4Mc2JA6lINzG7zoyyXVajIS2Ub1T0BamWnXJ1zmvopksFITiLOQySvjc6iQ49YlBL3m83OuE070NCI5td3yc2UjIPAA23fI_VojXOYuYzaa5mM8_RBbWL8iOcTUcHFlqJfjLTV4Fs16eD72w/p.gif)

Site is responsive to screen size
![](https://previews.dropbox.com/p/thumb/ABjvq3MqnJ76emPogqwZr5xUbMHi8BhZxfYEOggUiY_e5OWJRtyvBFRBv88JMWD_EFuovCX_TaACh7_SuKa-w9yWkRvSRuyd9nFINDo8qzmXOZWlNUmICPaFC504ahtxZwSFe1-YXXACjqgZBhX2ygQWhJfFqGkRCsKaS8LIpm4j08YzZ9uQSYOQ7vbWIjhpL4JlM0SRrPXX6Ekvi5G9wS2SVRu1tuBHakJHSw5suxuFLljLsLjP3jDP_RudyqqwExDlJUDTS2UKwzeg1Qsx6RaEd2EEJ29VTSjmR_R2waM-9UhI9kvwEsOX33nXo2_th5e4gJXqZyCkxcj1dN2kHrHV-7YypzsPMc2VINL8onc26irRAKZn3LlDW3Djgc9NVXzKVBNOfKwLzSn_PYfvfMf-0hKb06ggQpPGzQKPBd0bGupeHBpO9prrimKn1unMF6c/p.gif)

Popup works and user can click outside of box to exit
![](https://previews.dropbox.com/p/thumb/ABgXZZIcVcer_7oP_FMRvaNJgbi9cWsKMP4oUApvkFHR9gpg4cZgvXgu4CgIVcYM3B9a1mZFfOPdIKx5wnCniECvcPBFRNuuFi53yU3-J8dld_DLYeJLZhRlhg-yHrfT086uvDQDfJVM1oW4FI4Ru6mlxO9jIPkJ3wRZbXE6rsSJf4p2fWiDFZxh3tpShH_7uYt122c9SDo0uErqNB1c27SCRgyfRPO2wIr63iCsbF0sUJWLKtHagIgrrkB-PAC_38E-589Ybj3b4w6LtkbJ2FxVEcAnnHgQzX9o2kTIpmEwI6kc3aeMnT6v_gwvs9RHYArFIA4v00XLX8g4RvZfIp7l-FKLOrT3XjK8i4aA4mQCfGKsZUUq0Qad2vhx0ZPhpvg/p.gif)

### Reflection

* Did the topics discussed in your labs prepare you to complete the assignment? Be specific, which features in your weekly assignment did you feel unprepared to complete?

Yes, I would say that the project followed what we did in the labs, especially what we did with event listeners, APIs, and DOM methods. The feature that I felt the least prepared for was probably all the API calls. Although I feel that I understand them pretty thoroughly, I found myself looking back at the Giphy party lab the most because I needed to reference the syntax and code flow.

* If you had more time, what would you have done differently? Would you have added additional features? Changed the way your project responded to a particular event, etc.
  
I think I would want to spend some more time refactoring the API calling functions in order to be as reusable as possible. I already went in at the end of the lab to do this, but I feel like it could still be better. I'd also want pay more attention to and follow good-practice guidelines since I sometimes felt that my code consisted of a lot of "workarounds." 

Thinking of it more specifically, I would want to flesh out the popup boxes a lot more. Currently, they don't have a lot of information in them, so I want to spend more time with the available APIs to include more information. I'd also like to spend more time on the CSS to add animations.

* Reflect on your project demo, what went well? Were there things that maybe didn't go as planned? Did you notice something that your peer did that you would like to try next time?

I was able to get the basics of each of the core features pretty easily, but I ran into more trouble while dealing with some of the more fine-grained implementation details. This was especially true for the popup part, since I was able to get everything working on the console, but had a harder time getting it to display how I wanted. Another thing that was frustrating was adding the event handlers for each of the movie cards. I ran into a couple errors I was unsure how to get around, but I was able to find another method to accomplish the job.

### Open-source libraries used

- N/A

### Shout out

Shoutout to Mariam and Deland! We were partnered for the two days I worked on this project, and I was able to get a lot of feedback and help from them. I'd also like to shoutout Doris, Jenny, and Kian, who all helped me learn the skills needed to get this project done.
