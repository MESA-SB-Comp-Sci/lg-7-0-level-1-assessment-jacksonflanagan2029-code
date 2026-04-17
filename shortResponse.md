# Short Response — LG 7.0: Responsive Units

Answer each question in 2–3 sentences. 

---

## Question 1 — Describe

What is the difference between a static unit like `px` and a responsive unit like `%` or `vh`?

px is a fixed size, while % and vh can scale differently based on other variables. % scales off of the size of the parent element, while vh scales off of the user's screen height.

Describe what makes a unit responsive and why that matters when building a website.


Something that makes a unit responsive is a property which makes specific elements able to change sizes. This matters becuase the screen size differences are different between different devices. An element with a fixed size that works for one device might not work on a different one with a smaller or larger screen.





---

## Question 2 — Explain

Look at these two CSS rules:

```css
.image {
  width: 400px;
}

.image {
  width: 50%;
}
```

Explain what happens to the image on a small screen with each rule. Why does one behave better than the other?


The 1st image would appear larger than the 2nd image because a  smaller screen might have less pixels than a larger one. 400 px will only be seen on the device that has a screen that wide. % can change, if the parent element takes up a full screen of either device, the % will change based on how that element is scaled. Therefore, the % is better since its more reliable between difference devices and screen sizes.


