# front and back data

## web

### home

```js
let home = {
  'about-us': {
    id: 4,
    title: 'pharmacy',
    sub_title: 'sub title',
    about: 'we do what is good',
    user_id: 1,
    deleted_at: null,
    created_at: null,
    updated_at: null,
  },
  services: [
    {
      id: 1,
      name: 'web',
      desc: 'web services',
      icon: 'web.png',
      user_id: 1,
      deleted_at: null,
      created_at: null,
      updated_at: null,
    },
  ],
  'contact-us': {
    id: 2,
    phone: '123465789',
    email: 'email@email.com',
    user_id: 1,
    deleted_at: null,
    created_at: null,
    updated_at: null,
  },
  social: {
    id: 1,
    facebook: 'facebook.com',
    whatsapp: 'whatsapp.com',
    twitter: 'twitter.com',
    instagram: 'instagram.com',
    user_id: 1,
    deleted_at: null,
    created_at: null,
    updated_at: null,
  },
};
```

## /pharmacies

```js
let pharmacies = [
  {
    id: 2,
    name: 'Yemen',
    logo: '9876.pmg',
    about: 'Ali pharmacy',
    email: 'ali@email.com',
    is_full_time: 0,
    from: null,
    to: null,
    address: 'Yemen',
    lat: null,
    lng: null,
    user_id: 1,
    neighborhood_id: 1,
    deleted_at: null,
    created_at: null,
    updated_at: '2022-04-18T21:52:36.000000Z',
    user: {
      id: 1,
      name: 'super',
      email: 'super@gmail.com',
      email_verified_at: '2022-04-18T20:19:30.000000Z',
      created_at: '2022-04-18T20:19:30.000000Z',
      updated_at: '2022-04-18T20:19:30.000000Z',
    },
    social: null,
    neighborhood: {
      id: 1,
      name: 'Naif',
      directorate_id: 1,
      deleted_at: null,
      created_at: null,
      updated_at: null,
    },
  },
];
```

## /admin

### /ads

```js
let ads = [
  {
    id: 3,
    title: 'ad title',
    image: '1234.png',
    link: 'https:://google.com',
    ad_position: 'home',
    start_at: '2022-04-20',
    end_at: '2022-05-20',
    user_id: 1,
    deleted_at: null,
    created_at: '2022-04-20T21:02:40.000000Z',
    updated_at: '2022-04-20T21:02:40.000000Z',
  },
];
```

## /client
