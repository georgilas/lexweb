# Can ChatGPT write code?

I gave ChatGPT the following prompt:

```
I'll give you a table of letters and the numbers they represent:

Greek letter -> Number
Α -> 1
Β -> 2
Γ -> 3
Δ -> 4
Ε -> 5
Ζ -> 7
Η -> 8
Θ -> 9
Ι -> 10
Κ -> 20
Λ -> 30
Μ -> 40
Ν -> 50
Ξ -> 60
Ο -> 70
Π -> 80
Ρ -> 100
Σ -> 200
Τ -> 300
Υ -> 400
Φ -> 500
Χ -> 600
Ψ -> 700
Ω -> 800

For example, the Greek word ΑΝΗΡ ('man' in English) gives 1+50+8+100=159.

Now, write a complete web application, that inputs a Greek word and returns the sum of its letters. Display the result immediately after the user types letters. If he types spaces or numbers, ignore them.
```

It made a simple web app for me.
[URL](https://lexweb.surge.sh/)