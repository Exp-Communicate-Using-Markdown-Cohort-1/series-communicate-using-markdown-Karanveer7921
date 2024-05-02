# Learning Markdown Syntax
### Headers
There are 6 headers (h1 - h6) and are represented by using # - ######

### Images
We can add images in markdown with a link and providing an alt-text for screen readers or as a fallback in case the image fails to load.
To add image, we start with an exclamation symbol (!), followed by the alt-text in square brackets and lastly the link of image enclosed in parenthesis.

![Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)

### Code Blocks
We can add code blocks in markdown by enclosing the code text in 3 backticks

```
public class MarkDown {
  public static void main(String... args) {
    System.out.println("Hello MarkDown!");
  }
}
```

### Tasks List
Every item in tasks list should start with hyphen (-) sign, followed by X (checked) or Empty Space (unchecked) enclosed within square brackets. After that we write the content of that list item. Note : All these three elements in syntax of tasks list should be seperated by a space.

- [X] Step 1: Add headers
- [X] Step 2: Add an image
- [X] Step 3: Add a code example
- [X] Step 4: Make a task list
- [ ] Step 5: Merge your pull request
- [ ] Finish
