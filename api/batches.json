export async function onRequest(context) {
  const response = await fetch('https://nt.rarestudy.in/api/batches', {
    headers: { 'Content-Type': 'application/json' },
  });
  const data = await response.json();
  return new Response(JSON.stringify(data), {
    headers: {
      'Content-Type': 'application/json',
      'Access-Control-Allow-Origin': '*',
    },
  });
}
