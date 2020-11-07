
  h1 {
    text-transform: lowercase;
  }
  h2 {
    text-align: :right;
  } 
  h3 {
    font-size: 58px;
  }
  ### Learning Objectives
  - What is CSS?
    CSS stands for Cascading Style Sheets.
    We use CSS to add styles to the HTML elements on our page.
  - Connecting Style To Structure
    3 methods:
      - In-Line
      - Internal
      - External
    It is important to know when and why we would use each, along with advantages and disadvantages.
  - How the Internet/Browser Works
    As we are now pulling additional files into our index.html, how does the browser know where to pull in those files?
    The head section of the HTML is to transmit metadata, which provides important information about the website.
    The browser acts like a feeder that reads line by line, top to bottom.
    From there, it makes subsequent network calls to the URL provided which pulls in the requested information without replacing the current page. 
    To connect CSS files to our index.html we use a <link> tag.
    it requires the link itself and two attributes: rel & href.
    Rel is for the relation to the current file, for CSS, we use: 'stylesheet'
    Href is the reference path/URL to our stylesheet file: './styles.css'.
  - What Can We do with CSS?
    Before getting into what we can do with CSS, let's properly learn the syntax of CSS.
    It is constructed with the selector, curly braces, containing rules.
    The rules are a combination of PROPERTIES, and VALUES.
    Example:
    span {
      color: blue; /* Styles! */
      font-size: 20px;
      font-style: italic;
      line-height: 22px;
    }
    - Color
      There are two properties for colors depending on the use.
      1. Fonts/Texts - color
      2. Blocks/Containers - background-color
      For both properties, there is various ways to assign the values for color.
      Here are the common three:
        - RGB Values
          - used with rgb(numeric value, numeric value, numeric value);
          - Example: background-color: rgba(127, 134, 193, 0.43);
      
        - Hex Codes
          - base 16 code for rgb
          - Example: background-color: #48d1cc;
      
        - Color Names
    - Web Typography
    Majority of index.html is text! It is important to know how to style text according.
    Here are the common properties with example values for web typography.
    h1 {
      text-align: center; /* left, center, right, justify*/
      text-transform: capitalize; /* UPPERCASE, lowercase, Capitalize */
      text-decoration: underline; /* none, underline */
      line-height: 120px; /* number, px value*/
      font-weight: bold; /* normal, bold */
      font-style: italic; /* regular, italic */
      font-family: "Henny Penny", Arial, sans-serif; /* san-serif, serif */
      /* font-size: 150px; */
    }
  