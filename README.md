## Fusion Alliance Frontend Web Coding Challenge

### Rules of Engagement 

- You will start by forking this repo
- You can use any open source libraries you feel are appropriate
- You can freely use the internet for help
- You cannot copy anyone else's coding challenge implementation
- When done, you will issue a pull request
- Our code reviewer(s) should not need to talk to you in order to run your code (tests and app), so use this README for any instructions or environment setup/prerequisites

### Setup

1. You will be querying imgur's r/funny subreddit images. Make sure you can access the api. Try:

```
curl --header "Content-Type: application/json" --header "Authorization: Client-ID 648d825dc3960cb" https://api.imgur.com/3/gallery/r/funny
```

Feel free to use the same Client-ID of 648d825dc3960cb.

### App Requirements

**Note: We know that you likely cannot complete all of the listed tasks within the allotted time. Do as many as you can, and do them well.**

- Display a scrollable list of r/funny images with a title [Imgur Api Doc](https://api.imgur.com/endpoints/gallery#subreddit)
- Filter out NSFW images
- Implement pagination (Infinite scrolling is better)
- Implement refresh
- Cache imgur data in browser local storage so that you do not fetch new data every time
- Create a detail view when the user clicks on an image
- Create a custom view for the list item showing a rounded image, title, number of views, and number of upvotes
- Create separate views and/or styles for mobile (e.g. iPhone or Google Nexus) and desktop
- Implement unit tests
- Bonus points for using AngularJS (yes, we are in need of awesome software engineers with AngularJS experience)

