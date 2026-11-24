# Attendance Calculator

A browser tool that estimates monthly lecture attendance from a weekly total and attended count. It multiplies both counts by four and shows how many more lectures to attend in the projected month to reach 75% and 90%.

## Technologies

HTML, CSS and JavaScript. The calculation runs in the browser.

## Run locally

Clone the repository and open `index.html` in a modern browser. To serve it over HTTP, run:

```sh
git clone https://github.com/tanish1112/atennator.git
cd atennator
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). Python is only needed for the optional local server.

## Try an example

Enter **20** weekly lectures and **15** attended. The projected attendance is **75%**, and the calculator shows **12** more lectures to reach **90%** of the projected total. Use a weekly total greater than zero.
