# Curriculo_Hellen_Carvalho
const response = await fetch('https://curriculo-hellen-carvalho.onrender.com/ask', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify({ question: question, system: systemPrompt })
});
