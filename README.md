
# Collecting Twitter Data

Collecting data from twitter with python



## Authors

- [@LerekoQholosha](https://github.com/lerekoqholosha)


## API Reference

#### Get all items

```http
  GET /api/twitter
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `access_token` | `string` | **Required**. Your API key |
|`consumer_key`|`string`|**Required**. Your API Key|

#### Get item

```http
  GET /api/twitter/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### collect different attributes about data

Example of attributes to scrape Dates and Location.


## Usage/Examples

```pyhon
# We create a tweet list as follows:
tweets = extractor.user_timeline(screen_name="capetownfreeway",
                                 count=200,
                                 include_rts=False)
print(f"Number of tweets extracted: {len(tweets)}.\n")
```


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Support

For support, email lerekoqholosha9@gmail.com or join our Linkedin Community.


## 🚀 About Me
I'm a developer,Data Scientist and Account Manager...



