## Quantity Always Trumps Quality (https://blog.codinghorror.com/quantity-always-trumps-quality/)

<ul>
<li>Essential takeaway: worrying and fussing over work will prevent making really good work, because you won't learn from your mistakes and correct yourself. 
<li>Just build it! Don't theorize!
</ul>

## Clean Code (http://ptgmedia.pearsoncmg.com/images/9780132350884/samplepages/9780132350884.pdf)

<ul>
<li>Craftsmanship is important to writing successful code. This can be achieved through KNOWLEDGE and WORK. Later equals never, so do it right, and ship clean code, otherwise it can yield years of compounding issues and drive costs higher and higher.
<li>Code is the language in which we express the requirements. Writing messy code is like communicating poorly. It is your job as an engineer to defend the code.
<li>Clean code is elegant, efficient (no wasted cycles), with straightforward logic, and minimal dependencies. Clean code does ONE thing well. Bad code tempts the mess to grow! Keep it simple and direct. 
<li>We are authors, so write well! We are also Scouts, whose duty it is to keep the code clean where we see it can be improved/cleaned up.
</ul>

## Red, Green, Refactor (https://www.codecademy.com/articles/tdd-red-green-refactor)

<ul>
<li>The process of writing code can follow this pattern:
    <ul>
    <li>RED: think about WHAT you want to develop.
    <li>GREEN: think about HOW to make your tests pass.
    <li>REFACTOR: think about how to improve your existing implementation
    </ul>
<li>Planning is key, and will prevent wasting time. This process will allow for creating more efficient, clean code. 
</ul>

## Cycles of TDD (https://blog.cleancoder.com/uncle-bob/2014/12/17/TheCyclesOfTDD.html)

<ul>
<li>Engineers: make it work, make it right, make it fast. Getting software to work is only part of the job. 
<li> The three Laws of TDD:
    <ol>
    <li>You must write a failing test before you write any production code.
    <li>You must not write more of a test than is sufficient to fail, or fail to compile.
    <li>You must not write more production code than is sufficient to make the currently failing test pass.
    </ol>
<li>These are the nano-cycle of TDD, which you must follow on a second-by-second basis, and implement a dozen or so times before finishing a single unit test.
<li>The Red-Green-Refactor is the micro-cycle, or minute-by-minute process. You must:
    <ol>
    <li>Create a unit test that fails.
    <li>Write production code that makes that test pass.
    <li>Clean up the mess you just made.
    </ol>
<li> At the ten-minute level you will see the DECAMINUTE-BY-DECAMINUTE, or milli-cycle portion of the process. Here, test suites become more specific.
<li> Programmers make specific cases work by writing code that makes the general case work.
<li>HOUR BY HOUR primary cycle is BOUNDARIES, which drives us toward a Clean Architecture. Check architectural boundaries to ensure they're intact/not encroached upon.
</ul>