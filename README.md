<!DOCTYPE html>
<html>
  <head>
    <title>Just a Silly Little Page</title>
    <title>Image</title>
    <style>
      body {
        background-color: lightcoral;
      }
      .red-button {
        background-color: lightgoldenrodyellow;
        color: black;
        font: bolder;
        font-size: larger;
        font-family: "Times New Roman", Times, serif;
        font-style: italic;
        animation: moveLetters 3s;
      }
      .p1 {
        background-color: lightpink;
        font: bold;
        color: black;
        font-size: 16;
        font-style: italic;
        font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS",
          sans-serif;
      }

      .p2 {
        text-decoration: underline;
        font-size: 16;
        background-color: aquamarine;
        text-align: center;
        word-spacing: 0cap;
        border-bottom-left-radius: 2pc;
        border-bottom-right-radius: 2pc;
        border-width: 0.5cm;
      }

      .yellow-button {
        background-color: lightsalmon;
      }
      .p4 {
        font-size: smaller;
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
      }
      @keyframes moveLetters {
        0% {
          transform: translateY(0);
        }
        50% {
          transform: translateY(-20px);
        }
        100% {
          transform: translateY(0);
        }
      }
      .yellow-button {
        animation: moveLetters 2s;
      }
      .p5 {
        background-color: lightgreen;
        text-align: left;
      }
      .bt6 {
        animation: forwards;
      }
      .p7 {
        text-align: center;
        position: absolute;
        right: 90px;
        left: 500px;
        font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS",
          sans-serif;
      }
    </style>

  </head>
  <body>
    <button
      title="I see you there B!"
      class="red-button"
      onclick="
    alert('Good job so far!');
    "
    >
      Hello
    </button>

    <p title="p1" class="p1">
      This is quite a short paragraph, and from a semantic point of view, you
      would not expect it to have much of a deep meaning behind this sentence.
      However, since you have read up to here, your viewpoints may have changed,
      this might be due to the
      <button
        title="I see you there B!"
        class="yellow-button"
        onclick="
        alert('Hi B');
        "
      >
        narrator's
      </button>
      affect.
    </p>

    <p class="p2">
      “I will love you as misfortune loves orphans, as fire loves innocence, and
      as justice loves to sit and watch while everything goes wrong.”
    </p>
    <p class="p4">― Lemony Snicket, The Beatrice Letters</p>
    <script>
      alert("Hi B");
    </script>

    <p class="p5">
      "What is my perfect crime? I break into
      <button
        class="bt6"
        onclick="
      alert('nice one right');
      "
      >
        Tiffany's
      </button>
      at midnight. Do I go for the vault? No, I go for the chandelier. It's
      priceless. As I'm taking it down, a woman catches me. She tells me to
      stop. It's her father's business. She's Tiffany. I say no. We make love
      all night. In the morning, the cops come and I escape in one of their
      uniforms. I tell her to meet me in Mexico, but I go to Canada. I don't
      trust her. Besides, I like the cold. Thirty years later, I get a postcard.
      I have a son and he's the chief of police. This is where the story gets
      interesting. I tell Tiffany to meet me in Paris by the Trocadero. She's
      been waiting for me all these years. She's never taken another lover. I
      don't care. I don't show up. I go to Berlin. That's where I stashed the
      chandelier."
    </p>
    <p class="p7">
      "Yes, I have a dream. I want to own a decommissioned lighthouse. And I
      want to live at the top. And nobody knows I live there. And there's a
      button I can press and launch that lighthouse into space." -Stanley
    </p>

    <img src="oneimage.jpg" alt="character from /the office/" width="300px" />

  </body>
</html>
