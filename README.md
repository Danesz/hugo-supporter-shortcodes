# hugo-supporter-shortcodes

[Hugo](https://gohugo.io/) shortcodes for supporter pages: [Patreon](https://www.patreon.com/) and [Buy Me A Coffee](https://www.buymeacoffee.com/)

## Setup 
Copy the files to your into you Hugo project. (to the path where they are located in this repo: `layouts/shortcodes/` )

## How to use

In your Markdown post you can do:

### Patreon
```
{{< patreon user="37212546" color="#2ecc71" title="Become a Patron" >}}
```
- `user`: 
When you create a Patreon button [here](https://www.patreon.com/dashboard/widgets), you get a URL inside the widget: `https://www.patreon.com/bePatron?u=37212546`. The ID (numbers) after the `u=` parameter is the user .

- `color`:
The color of the Patreon button (background).

- `title`:
The text on the button.

### Buy Me A Coffee

```
{{< buymeacoffee user="tweakedtech" color="#2ecc71" title="Buy me a coffee" >}}
```

- `user`: 
On the [Dashboard]( https://www.buymeacoffee.com/dashboard) you can see your own personal URL, something like this: `https://www.buymeacoffee.com/tweakedtech`.
`tweakedtech` is the user in this case

- `color`:
The color of the Patreon button (background).

- `title`:
The text on the button.

## Example

[https://danieldallos.com/posts/2020/07/how-i-built-6-1-apps-in-one-day/](https://danieldallos.com/posts/2020/07/how-i-built-6-1-apps-in-one-day/#support)
