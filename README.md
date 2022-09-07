# It's a carrot 😎


###  What do you mean?

👉 https://lexisseoul.com/2016/08/02/korean-slang-%EB%8B%B9%EA%B7%BC/  

<br />

``` js
function App() {
  let [request, setRequest] = useState(0);
  const [response, setResponse] = useState(false);

  const onClick = () => {
    setRequest((current) => current + 1);
    setResponse(true);
  };

  let myHeart = ' '.repeat(request / 1) + '🥕'.repeat(request);

  return (
    <div>
      <h1>Want to try?</h1>
      <p>
        {response ? "It's a Carrot 😎 " : ''}
        {myHeart}
      </p>
      <button onClick={onClick}>{response ? 'OF COURSE' : 'MY HEART'}</button>
    </div>
  );
```
