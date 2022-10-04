# TDD Best Practice

I've been writing TDD (Test-Driven Development) code since my first programming job in 2007 and it changed my development life. It made me a better developer and write better, more thoughtful code. This is not a tutorial on writing TDD so if you haven't done it before then I recommend you search for them before coming to this repository.

In TDD, the principles are you write the test, watch it fail for the right reason, fix it with minimal change.
If your test doesn't fail for the right reason, make sure it does. You don't want to fix a test only for it to still fail and you end up doing more than you should.

I have used C# as my language of choice to demonstrate these best practices but there is no reason why you couldn't apply them in other languages.

### Why would you write code TDD?
You will eventually think how will I test this? I need to keep this simple.

## Best practice

Remember!
- Write the test first.
- Watch it fail for the right reason - if it doesn't, make sure it does.
- A test that does not compile is a failing test.
- Fix the test.
- Refactor if need be.
- Do not make a test too complicated to maintain.

## Examples
All the examples of best practice are listed below.

- Assert has a > b but only one way tested
- If statements likely to be a smell
- Abuse of InlineData, too many parameters handling too many scenarios in one test
- Booleans to decide with Asserts
- Null checks newer testall/impossible code
- Use SonarQube - It can be an education to catch logic you miss.
- Tackle the coverage to reduce the noise when adding new code
- Class testing another class
- Writing unit tests after the code is written
- Write test-driven code
