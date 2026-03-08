sequenceDiagram
    participant browser
    participant server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa
    activate server
    server-->>browser: HTML document
    deactivate server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    activate server
    server-->>browser: the css file
    deactivate server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.js
    activate server
    server-->>browser: the JavaScript file
    deactivate server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    activate server
    server-->>browser: [
    {
        "content": "asdfghjk",
        "date": "2026-03-07T17:42:53.381Z"
    },
    {
        "content": "jj",
        "date": "2026-03-07T17:43:17.406Z"
    },
    {
        "content": "guppi",
        "date": "2026-03-07T18:24:50.612Z"
    },
    {
        "content": "ljljb",
        "date": "2026-03-07T18:55:07.823Z"
    },
    {
        "content": "lkm,;l",
        "date": "2026-03-07T18:56:04.115Z"
    },
    {
        "content": "",
        "date": "2026-03-07T18:56:06.833Z"
    },
    {
        "content": "anyone active as of March 7 2026?",
        "date": "2026-03-07T18:56:29.051Z"
    },
    {
        "content": "yoyoyo",
        "date": "2026-03-07T19:04:03.990Z"
    },
    {
        "content": "im a fkin loser",
        "date": "2026-03-07T19:04:24.366Z"
    },
    {
        "content": "lessgoo",
        "date": "2026-03-07T19:07:11.121Z"
    },
    {
        "content": "",
        "date": "2026-03-07T19:07:11.456Z"
    },
    {
        "content": "lol what did you loose fkin loser? where are u from?",
        "date": "2026-03-07T19:10:54.665Z"
    },
    {
        "content": "Have a day",
        "date": "2026-03-07T19:58:58.941Z"
    },
    {
        "content": "i need a job",
        "date": "2026-03-07T20:04:24.950Z"
    },
    {
        "content": "aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa",
        "date": "2026-03-07T20:28:29.820Z"
    },
    {
        "content": "adding a test ",
        "date": "2026-03-07T20:36:07.545Z"
    },
    {
        "content": "皆さん、こんにちは",
        "date": "2026-03-07T20:36:16.240Z"
    },
    {
        "content": "konichawagwan",
        "date": "2026-03-07T20:45:21.664Z"
    },
    {
        "content": "hallo 1337 ",
        "date": "2026-03-07T20:54:00.786Z"
    },
    {
        "content": "hello",
        "date": "2026-03-07T21:17:05.704Z"
    },
    {
        "content": "hi all, how r u?",
        "date": "2026-03-07T21:18:59.287Z"
    },
    {
        "content": "hi",
        "date": "2026-03-07T21:27:20.077Z"
    },
    {
        "content": "hi",
        "date": "2026-03-07T21:28:19.149Z"
    },
    {
        "content": "hallo 1337 SPA",
        "date": "2026-03-07T21:59:14.546Z"
    },
    {
        "content": "hsl",
        "date": "2026-03-07T22:01:38.264Z"
    },
    {
        "content": "llll",
        "date": "2026-03-07T22:25:38.223Z"
    },
    {
        "content": "x",
        "date": "2026-03-07T22:46:59.397Z"
    },
    {
        "content": "Malala",
        "date": "2026-03-07T22:55:46.171Z"
    },
    {
        "content": "yoooo",
        "date": "2026-03-07T22:56:49.037Z"
    },
    {
        "content": "wassup gang",
        "date": "2026-03-07T23:01:02.993Z"
    },
    {
        "content": "new one",
        "date": "2026-03-07T23:07:49.451Z"
    },
    {
        "content": "260308",
        "date": "2026-03-07T23:44:36.137Z"
    },
    {
        "content": "wahid was here!",
        "date": "2026-03-08T00:46:43.786Z"
    },
    {
        "content": "lkj",
        "date": "2026-03-08T01:28:11.149Z"
    },
    {
        "content": "Hola",
        "date": "2026-03-08T01:36:58.161Z"
    },
    {
        "content": "okau",
        "date": "2026-03-08T02:37:10.379Z"
    },
    {
        "content": "gsg",
        "date": "2026-03-08T05:06:05.753Z"
    },
    {
        "content": "new n",
        "date": "2026-03-08T05:34:56.398Z"
    },
    {
        "content": "hi",
        "date": "2026-03-08T05:35:51.757Z"
    },
    {
        "content": "bur",
        "date": "2026-03-08T05:35:59.416Z"
    },
    {
        "content": "json",
        "date": "2026-03-08T05:37:53.870Z"
    },
    {
        "content": "yo chat",
        "date": "2026-03-08T05:51:06.325Z"
    },
    {
        "content": "https://youtu.be/xMHJGd3wwZk?si=eB3O7yspL2kt-PbB",
        "date": "2026-03-08T05:59:55.137Z"
    },
    {
        "content": "gegeg",
        "date": "2026-03-08T06:02:30.766Z"
    },
    {
        "content": "fsssd",
        "date": "2026-03-08T06:37:38.629Z"
    },
    {
        "content": "gdhdnghdf",
        "date": "2026-03-08T06:37:46.046Z"
    },
    {
        "content": "good",
        "date": "2026-03-08T06:39:00.745Z"
    },
    {
        "content": "goodness",
        "date": "2026-03-08T06:40:09.642Z"
    },
    {
        "content": "Mur",
        "date": "2026-03-08T06:54:38.792Z"
    },
    {
        "content": "MurMur",
        "date": "2026-03-08T07:02:15.209Z"
    },
    {
        "content": "TWICE is the best girlgroup",
        "date": "2026-03-08T07:31:23.565Z"
    },
    {
        "content": "Minatozaki Sana <3",
        "date": "2026-03-08T07:44:32.475Z"
    },
    {
        "content": "Yoo Jeongyeon <3",
        "date": "2026-03-08T07:50:21.031Z"
    },
    {
        "content": "marco",
        "date": "2026-03-08T08:18:01.692Z"
    },
    {
        "content": "Hola, Ale.",
        "date": "2026-03-08T09:03:49.932Z"
    },
    {
        "content": "ohaaaa!",
        "date": "2026-03-08T09:16:30.157Z"
    },
    {
        "content": "haab",
        "date": "2026-03-08T09:44:28.340Z"
    },
    {
        "content": "heloust",
        "date": "2026-03-08T09:51:50.560Z"
    },
    {
        "content": "piczka",
        "date": "2026-03-08T09:56:22.482Z"
    },
    {
        "content": "yes",
        "date": "2026-03-08T10:14:10.641Z"
    },
    {
        "content": "no",
        "date": "2026-03-08T10:14:22.598Z"
    },
    {
        "content": "yr",
        "date": "2026-03-08T10:14:34.706Z"
    },
    {
        "content": "hey ",
        "date": "2026-03-08T10:25:48.526Z"
    },
    {
        "content": "wassup",
        "date": "2026-03-08T11:02:24.535Z"
    },
    {
        "content": "ayo",
        "date": "2026-03-08T11:24:00.991Z"
    },
    {
        "content": "im handsome",
        "date": "2026-03-08T11:35:08.016Z"
    },
    {
        "content": "neppari",
        "date": "2026-03-08T11:52:41.149Z"
    },
    {
        "content": "neppari_2",
        "date": "2026-03-08T12:12:32.012Z"
    },
    {
        "content": "",
        "date": "2026-03-08T12:31:35.328Z"
    },
    {
        "content": "Hey there!",
        "date": "2026-03-08T12:32:47.154Z"
    },
    {
        "content": "blanco",
        "date": "2026-03-08T12:34:02.749Z"
    },
    {
        "content": "Hey There Mate!",
        "date": "2026-03-08T12:38:12.380Z"
    },
    {
        "content": "[cp] Hi cs mates",
        "date": "2026-03-08T12:46:33.574Z"
    },
    {
        "content": "[cp] Keeping move, mates",
        "date": "2026-03-08T12:48:28.371Z"
    },
    {
        "content": "Let's go lads!",
        "date": "2026-03-08T12:57:49.524Z"
    },
    {
        "content": "Naice",
        "date": "2026-03-08T13:00:44.848Z"
    },
    {
        "content": "Noice",
        "date": "2026-03-08T13:15:47.561Z"
    },
    {
        "content": "isoolut",
        "date": "2026-03-08T13:15:48.262Z"
    },
    {
        "content": "naive",
        "date": "2026-03-08T13:27:46.220Z"
    },
    {
        "content": "asdd",
        "date": "2026-03-08T13:30:16.889Z"
    },
    {
        "content": "Jesus Save",
        "date": "2026-03-08T13:58:31.162Z"
    },
    {
        "content": "Lamb of God",
        "date": "2026-03-08T13:59:28.806Z"
    },
    {
        "content": "https://www.youtube.com/watch?v=yDdyDDAWRcM",
        "date": "2026-03-08T14:07:22.136Z"
    },
    {
        "content": "eläke juoksee, minä en",
        "date": "2026-03-08T14:13:03.589Z"
    },
    {
        "content": "",
        "date": "2026-03-08T14:16:34.429Z"
    },
    {
        "content": "test",
        "date": "2026-03-08T14:24:08.174Z"
    },
    {
        "content": "test",
        "date": "2026-03-08T14:27:15.768Z"
    },
    {
        "content": "1111",
        "date": "2026-03-08T14:27:40.786Z"
    },
    {
        "content": "test",
        "date": "2026-03-08T14:28:22.127Z"
    },
    {
        "content": "CLEAR",
        "date": "2026-03-08T14:30:20.114Z"
    },
    {
        "content": "iwashere",
        "date": "2026-03-08T14:36:10.556Z"
    },
    {
        "content": "was?",
        "date": "2026-03-08T14:57:04.611Z"
    },
    {
        "content": "Have a nice day!",
        "date": "2026-03-08T15:08:33.321Z"
    },
    {
        "content": "Hello frog!",
        "date": "2026-03-08T15:08:54.321Z"
    },
    {
        "content": "hey1",
        "date": "2026-03-08T15:32:18.386Z"
    },
    {
        "content": "test",
        "date": "2026-03-08T15:32:34.724Z"
    },
    {
        "content": "yo",
        "date": "2026-03-08T15:41:27.660Z"
    },
    {
        "content": "Have a day",
        "date": "2026-03-08T15:42:48.208Z"
    },
    {
        "content": "Single Page: Have a day",
        "date": "2026-03-08T15:44:01.519Z"
    },
    {
        "content": "hola que tal",
        "date": "2026-03-08T15:46:25.599Z"
    }
    ]
    deactivate server

    Note right of browser: The browser executes the callback function that renders the notes
