https://gralhix.com/list-of-osint-exercises/osint-exercise-012/

The screenshot below shows satellite imagery from a coastal area. Each red pixel represents a 30 metre centre point containing a thermal anomaly. The data is from January.  
Please analyse the screenshot and answer the following questions:  
  
a) Which website was used to produce the image below?  
b) Which is the country seen in the image?  
c) The screenshot shows data from a specific date. Which is the date?

### Information gathered
- The image was taken in January (not necessarily this year)

## Process
#### Which website was used to produce the photo?
1. There are a couple of ways of doing this. The 2 that came to mind were: exactly describing the UI of the image to an AI model with access to internet or reverse image searching.
2. I chose to exactly describe the UI to chatGPT and he returned me the correct website.

**NASA's FIRMS**

#### Which is the country seen in the image?
1. The world is too big to manually search for the country, so I had to narrow down my searching.
2. I first excluded every country not on the western coast.
3. Considering that the fire happened in January, it is highly possible that the country is in the southern hemisphere.
4. This narrows down my search quite a bit.
5. Now I manually searched every country on the western coast on the southern hemisphere. I found that Chile was matching the image.

**Chile**

#### Which is the specific date of the image?
1. This was a tricky one. In the exercise it is mentioned that the image is form January, but it is not said that it was January this year. It could be any January.
2. I asked chatGPT: In which January did Chile experience major forest fires. I got the response of 2017.
3. I cheched every single day from 1.1.2017-31.1.2017. I the exact thermal image and found the answer.

**26.1.2017**
