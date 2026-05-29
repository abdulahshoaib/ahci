---
title: Bad Website Design Examples
weight: 1
---

# Bad Website Design Examples

Bad website design happens when a website makes it difficult for users to understand, navigate, read, or complete tasks. A bad website may still function technically, but it fails from a usability and user experience point of view.

Common problems include:

- unclear purpose
- confusing navigation
- poor visual hierarchy
- cluttered layout
- weak readability
- low contrast
- inconsistent UI elements
- hidden or unclear actions
- poor mobile usability
- confusing forms

Each example below is rendered inside a sandboxed frame so the sample HTML is separated from the rest of the notes site.

```mermaid
flowchart TD
    T["Bad Website Design Examples"]
    T --> S1["1. Visuals Over Clarity"]
    T --> S2["2. No Clear Reading Flow"]
    T --> S3["3. Poor Readability"]
    T --> S4["4. Lack of Visual Hierarchy"]
    T --> S5["5. Content Overload"]
    T --> S6["6. Extreme Minimalism"]
    T --> S7["7. Inconsistent UI Elements"]
    T --> S8["8. Weak Primary Action"]
    T --> S9["9. Confusing Forms"]
    T --> S10["10. Poor Mobile Touch Targets"]
    T --> Sx["More sections"]
```

## 1. Visuals Over Clarity

Some websites focus too much on artistic presentation and forget the user's main goal.

Example problem:

A restaurant website may look visually creative, but users cannot quickly find:

- menu
- booking button
- location
- opening hours

Bad rendered example:

{{< rendered-html >}}
<div>
  <header>
    <h1 class="huge-logo">BRAND</h1>
  </header>

  <main>
    <div class="abstract-graphics">
      <p>Experience the essence of taste through fire and form.</p>
    </div>

    <nav>
      <a href="#">01</a>
      <a href="#">02</a>
      <a href="#">03</a>
    </nav>
  </main>
</div>
{{< /rendered-html >}}

Why this is bad:

- The website does not clearly explain what it is.
- Navigation labels are unclear.
- Important actions are hidden.
- Users must work too hard to find basic information.

Better rendered example:

{{< rendered-html >}}
<header>
  <h1>BRUTO Restaurant</h1>

  <nav>
    <a href="/menu">Menu</a>
    <a href="/reservations">Reserve a Table</a>
    <a href="/location">Location</a>
  </nav>
</header>
{{< /rendered-html >}}

## 2. No Clear Reading Flow

Some websites use experimental layouts with scattered text, moving images, vertical labels, and unusual placement.

Bad rendered example:

{{< rendered-html >}}
<main class="collage-layout">
  <p class="rotated-text">Menu</p>
  <img src="food.jpg" alt="Restaurant food">
  <p class="floating-note">Seasonal tasting experience</p>
  <a class="hidden-link" href="/book">Book</a>
</main>
{{< /rendered-html >}}

Why this is bad:

- Users do not know where to look first.
- Important links are not obvious.
- Decorative layout interferes with usability.
- The website feels confusing instead of helpful.

Better rendered example:

{{< rendered-html >}}
<main>
  <section>
    <h1>Seasonal Tasting Menu</h1>
    <p>Book a multi-course dining experience.</p>
    <a href="/book" class="primary-button">Book a Table</a>
  </section>
</main>
{{< /rendered-html >}}

## 3. Poor Readability

Readability problems happen when text is hard to read because of bad color, spacing, font choice, or layout.

Bad rendered example:

{{< rendered-html >}}
<section style="background: repeating-linear-gradient(45deg, #111, #111 8px, #555 8px, #555 16px); color: lime; padding: 1rem;">
  <p>
    Welcome to our website. Here you can find information about our services,
    history, contact details, updates, events, and announcements.
  </p>
</section>
{{< /rendered-html >}}

Why this is bad:

- Bright text on a busy background is hard to read.
- Large text blocks become tiring.
- Poor contrast reduces accessibility.
- Users may leave before reading the content.

Better rendered example:

{{< rendered-html >}}
<section style="background-color: #111; color: white; padding: 1rem;">
  <h1>About Us</h1>
  <p>
    Learn about our services, history, events, and contact information.
  </p>
</section>
{{< /rendered-html >}}

## 4. Lack of Visual Hierarchy

A website has poor hierarchy when everything looks equally important.

Bad rendered example:

{{< rendered-html >}}
<main>
  <a href="#">Jobs</a>
  <a href="#">Housing</a>
  <a href="#">Services</a>
  <a href="#">Community</a>
  <a href="#">For Sale</a>
  <a href="#">Discussion Forums</a>
  <a href="#">Events</a>
</main>
{{< /rendered-html >}}

Why this is bad:

- All links have the same visual weight.
- Users cannot quickly identify important sections.
- The page feels like a wall of links.
- New users receive little guidance.

Better rendered example:

{{< rendered-html >}}
<main>
  <h1>Find What You Need</h1>

  <section>
    <h2>Main Categories</h2>
    <a href="/jobs">Jobs</a>
    <a href="/housing">Housing</a>
    <a href="/services">Services</a>
  </section>

  <section>
    <h2>More</h2>
    <a href="/community">Community</a>
    <a href="/events">Events</a>
  </section>
</main>
{{< /rendered-html >}}

## 5. Content Overload

Some websites try to show too much information at once.

Bad rendered example:

{{< rendered-html >}}
<section>
  <h1>Government Services</h1>

  <div class="overlay">
    <a href="#">Governor</a>
    <a href="#">News</a>
    <a href="#">Taxes</a>
    <a href="#">Licenses</a>
    <a href="#">Jobs</a>
    <a href="#">Education</a>
    <a href="#">Health</a>
    <a href="#">Transport</a>
    <a href="#">Public Safety</a>
  </div>
</section>
{{< /rendered-html >}}

Why this is bad:

- Too many options compete for attention.
- Users must search instead of being guided.
- Dense link panels feel cluttered.
- Important services are not prioritized.

Better rendered example:

{{< rendered-html >}}
<section>
  <h1>How Can We Help?</h1>

  <div class="service-grid">
    <a href="/renew-license">Renew Driver License</a>
    <a href="/pay-taxes">Pay Taxes</a>
    <a href="/find-job">Find Jobs</a>
    <a href="/health-services">Health Services</a>
  </div>
</section>
{{< /rendered-html >}}

## 6. Extreme Minimalism

Minimal design becomes bad when it removes too much context.

Bad rendered example:

{{< rendered-html >}}
<main>
  <a href="#">Annual Report</a><br>
  <a href="#">Letters</a><br>
  <a href="#">News</a><br>
  <a href="#">Contact</a><br>
</main>
{{< /rendered-html >}}

Why this is bad:

- The site may look unfinished.
- There is no clear structure.
- Users may think the page failed to load.
- The design does not match modern expectations.

Better rendered example:

{{< rendered-html >}}
<header>
  <h1>Berkshire Hathaway</h1>
  <p>Official company information and investor resources.</p>
</header>

<main>
  <section>
    <h2>Investor Resources</h2>
    <a href="/annual-report">Annual Report</a>
    <a href="/letters">Shareholder Letters</a>
  </section>
</main>
{{< /rendered-html >}}

## 7. Inconsistent UI Elements

Inconsistency happens when buttons, colors, fonts, spacing, and components change without reason.

Bad rendered example:

{{< rendered-html >}}
<button style="background: blue; border-radius: 4px;">Submit</button>
<button style="background: green; border-radius: 30px;">Cancel</button>
<button style="background: red; font-family: serif;">Continue</button>
{{< /rendered-html >}}

Why this is bad:

- Users cannot predict how elements behave.
- The interface feels unprofessional.
- Different styles send mixed signals.
- It reduces trust.

Better rendered example:

{{< rendered-html >}}
<button class="button button-primary">Submit</button>
<button class="button button-secondary">Cancel</button>
<button class="button button-primary">Continue</button>
{{< /rendered-html >}}

## 8. Weak Primary Action

A common UI mistake is making primary and secondary actions look the same.

Bad rendered example:

{{< rendered-html >}}
<div>
  <button>Cancel</button>
  <button>Delete Account</button>
</div>
{{< /rendered-html >}}

Why this is bad:

- The dangerous or important action is not clearly distinguished.
- Users may click the wrong button.
- The interface does not guide decision-making.

Better rendered example:

{{< rendered-html >}}
<div>
  <button class="secondary">Cancel</button>
  <button class="danger">Delete Account</button>
</div>
{{< /rendered-html >}}

## 9. Confusing Forms

Bad forms do not guide users properly before or after submission.

Bad rendered example:

{{< rendered-html >}}
<form>
  <input type="email" placeholder="Email">
  <input type="password" placeholder="Password">

  <p style="color: red;">Error</p>

  <button>Submit</button>
</form>
{{< /rendered-html >}}

Why this is bad:

- The error message is vague.
- It only uses color to communicate the problem.
- The user does not know how to fix the issue.

Better rendered example:

{{< rendered-html >}}
<form>
  <label for="email">Email address</label>
  <input id="email" type="email" aria-describedby="email-error">

  <p id="email-error">
    Enter a valid email address, for example name@example.com.
  </p>

  <button>Create Account</button>
</form>
{{< /rendered-html >}}

## 10. Poor Mobile Touch Targets

Small clickable areas are bad for mobile users.

Bad rendered example:

{{< rendered-html >}}
<nav>
  <a href="/home">Home</a>
  <a href="/menu">Menu</a>
  <a href="/contact">Contact</a>
</nav>
{{< /rendered-html >}}

Why this is bad:

- Links may be too small to tap accurately.
- Users can tap the wrong item.
- Mobile navigation becomes frustrating.

Better rendered example:

{{< rendered-html >}}
<nav class="mobile-nav">
  <a class="touch-target" href="/home">Home</a>
  <a class="touch-target" href="/menu">Menu</a>
  <a class="touch-target" href="/contact">Contact</a>
</nav>
{{< /rendered-html >}}

## 11. Bad Date Input Pattern

A bad date input can make simple tasks harder, especially on mobile.

Bad rendered example:

{{< rendered-html >}}
<label>Date of birth</label>

<select>
  <option>Day</option>
</select>

<select>
  <option>Month</option>
</select>

<select>
  <option>Year</option>
</select>
{{< /rendered-html >}}

Why this is bad:

- Long dropdowns are slow.
- Selecting years can be frustrating.
- It increases effort for a simple input.

Better rendered example:

{{< rendered-html >}}
<fieldset>
  <legend>Date of birth</legend>

  <label>
    Day
    <input type="text" inputmode="numeric" maxlength="2">
  </label>

  <label>
    Month
    <input type="text" inputmode="numeric" maxlength="2">
  </label>

  <label>
    Year
    <input type="text" inputmode="numeric" maxlength="4">
  </label>
</fieldset>
{{< /rendered-html >}}

## 12. Wrong Control Type

Using the wrong input control creates confusion.

Bad rendered example:

{{< rendered-html >}}
<form>
  <h2>Video Settings</h2>

  <label>
    <input type="checkbox">
    Autoplay
  </label>

  <label>
    <input type="checkbox">
    Subtitles
  </label>

  <button>Save</button>
</form>
{{< /rendered-html >}}

Why this can be bad:

- Checkboxes with a Save button suggest changes happen later.
- For immediate settings, toggle switches are clearer.
- The control does not match the behavior.

Better rendered example:

{{< rendered-html >}}
<section>
  <h2>Video Settings</h2>

  <label>
    Autoplay
    <input type="checkbox" role="switch">
  </label>

  <label>
    Subtitles
    <input type="checkbox" role="switch">
  </label>
</section>
{{< /rendered-html >}}

## Final Notes

Bad website design is not only about ugly visuals. A website is badly designed when users cannot easily understand what it is, where to go, what to click, or how to complete their goal.

A better website should:

- make the main purpose obvious
- use clear navigation
- show strong visual hierarchy
- keep text readable
- avoid unnecessary clutter
- use consistent UI elements
- support mobile users
- give clear feedback
- make forms simple and understandable

Source: [DesignRush: Bad Website Design Examples][1]

[1]: https://www.designrush.com/agency/website-design-development/trends/bad-websites "Bad Website Design Examples: 21 Sites and What Went Wrong"
