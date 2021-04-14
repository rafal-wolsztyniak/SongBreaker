
## Hello,  SFMC Developers!

This is a repository for the solution that won in the **Efficiency** category on **[HowToSFMC](https://www.howtosfmc.com/posts/one-more-time-winners-announced/)**. The overall goal of the challenge was to generate the lyrics of the Daft Punk classic hit "One More Time" using Server-Side JavaScript in Marketing Cloud.

The **Efficiency** category itself was described as follows:

> Efficiency: The challenge lyrics are 2303 characters long, and your job is to find the least amount of characters necessary in SSJS to output these lyrics. This challenge will be measured solely via the character count. We will be utilizing https://www.charactercountonline.com/ to count the characters in your submission.

With my solution I've managed to output the lyrics with just 693 characters or almost exactly 30% of the original character count.


---


## The Repository

You'll find three files:
- `00 - SongBreaker` 
   - This is a page that generates the code for the words and structure strings that are then used in a minimized versions
   - This code will not run CloudPages - it uses newer JS capabilities to work with the arrays
   - It wasn't sensible to build pattern recognition for just one song, so any repeating sequences of words need to be found manually
   - **[Click here](https://hellosfmc.com/SongBreaker.html)** to see the script in action and possibly break other songs
- `01 - Original Submission - 693 characters`
    - The submitted solution that won
- `02 - Optimized After the Submission - 664 characters`
    - I couldn't help but try to optimize it a bit more and was able to cut the total length a bit and fix the obvious blunder I had made with conditionals in the original submission.

Visit **[my article on HowToSFMC](https://www.howtosfmc.com/posts/one-more-time-efficiency-winner/)** to learn how the submitted solution works.

Cheers

[Rafał](https://www.linkedin.com/in/rafal-wolsztyniak/)
