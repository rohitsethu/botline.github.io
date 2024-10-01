<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Voice Assistant</title>
</head>
<body>
  <h1>AI Voice Assistant</h1>
  <button onclick="startRecording()">Start Speaking</button>
  <button onclick="speak('Hello, how can I assist you?')">Test Response</button>
  
  <script>
    // Text-to-Speech (Output)
    function speak(text) {
      const speech = new SpeechSynthesisUtterance(text);
      speechSynthesis.speak(speech);
    }

    // Speech Recognition (Input)
    function startRecording() {
      const recognition = new (window.SpeechRecognition || window.webkitSpeechRecognition)();
      recognition.lang = 'en-US';
      recognition.onresult = (event) => {
        const transcript = event.results[0][0].transcript;
        console.log("You said:", transcript);
        speak(`You said: ${transcript}`);
        // Send the transcript to a Python backend for AI processing if needed
      };
      recognition.start();
    }
  </script>
</body>
</html>
