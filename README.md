# Risk Ledger Frontend Code Exercise

Thank you for applying to Risk Ledger 🎉.

## **Existing Code**

We understand completing a take-home technical exercise can be quite an ask, particularly if you are still in your current role, have personal commitments or are applying for multiple companies at once.

In lieu of completing the exercise below, we also accept other works, this could be contributions to open-source or internal projects (you have permission to share).

We do however ask that:

- what you submit is solely by you, or has significant contributions from you,
- we can verify this, i.e. with commit history,
- and it still meets our [What We're Looking For](#what-were-looking-for) criteria below.

## Code Exercise

If you don't have any existing code you can show us, we've put together a code exercise for you to complete in your own time.

We would like you to build a frontend single-page application, using any modern web framework of your choice. Your app should use the [Spotify Web API](https://developer.spotify.com/documentation/web-api/)  to meet the below requirements, using the Implicit Grant Flow described within the documentation for authentication. 

- A user should be able to view a grid of their recently played tracks.
    - This should include a relevant image for each track.
    - When scrolling, it should fetch more results & display them.
    
- In a sidebar, a user should be able to view a list of all recently played artists.
    - This should be in order of most recently played.
    - On click of an artist, the grid of recently played tracks should be filtered by the relevant artist.
    - On refresh of the page, any applied filter should be persisted.

- The displayed data should automatically update when a user listens to a new track (within 30 seconds).

Please include a README detailing how we can run your submission, the trade-offs you made, and how you'd improve on your submission.

### **What We're Looking For**

**We value quality over completeness.** What we are trying to assess is your thought process and approach to problem-solving. It is okay to leave something aside as long as you call it out in your README.

**We'd like to see testing,** and if you run out of time, we'd like to see code that is testable, and documentation in your README for how you would test your submission if given more time.

**Security is important.** If you don't address potential security issues in your submission, please document what they might be and how you would fix them if given more time.

We use [Vue 2](https://vuejs.org/) internally, however we'd prefer you use whatever framework you feel strongest in, rather than use this exercise as an opportunity to learn Vue.

We ask you don't spend more than **four hours** on this exercise.

### **How To Submit**

You may submit your code to us either on a hosted platform, i.e. GitHub or BitBucket, or as an archive file over email.