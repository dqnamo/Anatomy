
<img width="552" alt="CleanShot 2021-04-25 at 09 41 24@2x" src="https://user-images.githubusercontent.com/25507937/115986906-7b80e400-a5aa-11eb-8a2a-e1d2b0fe8630.png">

Items marked with ':heavy_dollar_sign:' are paid products or services.
Items marked with ':gem:' are products or services that have both free and paid versions.

## Core
These are the things that are at the heart of the operation.

1. Macbook Pro :heavy_dollar_sign:
3. Ruby
4. Ruby on Rails

## Text Editor
Where the magic happens. 

1. Sublime Text :heavy_dollar_sign:
   * Gravity Theme
   * Monokai Pro(Spectrum) syntax color scheme :heavy_dollar_sign:
   * Monolisa font :heavy_dollar_sign:
    
#### 📦 Packages
* A file icon
* Rails Partial
* Rails latest migration
* Sublime Linter
* Sublime Linter - Rubocop
* SideBar Enchancements
* Zen tabs
* Tabnine (More on this later!) :gem:

#### Sublime settings file
```json
{
	"font_face": "MonoLisa",
	"theme": "Gravity.sublime-theme",
	"rulers": [120],
	"color_scheme": "Packages/Theme - Monokai Pro/Monokai Pro (Filter Spectrum).sublime-color-scheme",
	"gravity_highlight_color_green": true,
	"gravity_title_bar": true,
	"font_size": 13,
	"ignored_packages":
	[
		"Vintage",
	],
	"highlight_modified_tabs": false,
	"detect_indentation": true,
	"tab_size": 2,
	"translate_tabs_to_spaces": true,
	"auto_complete": true,
	"auto_complete_triggers":
	[
		{
			"characters": ".(){}[],'\"=<>/\\+-|&*%=$#@! ",
			"selector": "source.python",
		},
		{
			"characters": ":.(){}[],'\"=<>/\\+-|&*%=$#@! ",
			"selector": "source & - source.python - constant.numeric",
		},
		{
			"characters": " qazwsxedcrfvtgbyhnujmikolpQAZWSXEDCRFVTGBYHNUJMIKOLP",
			"selector": "text",
		}
	],
}
```

...and here is how it looks.
<img width="1792" alt="CleanShot 2021-04-25 at 10 19 18@2x" src="https://user-images.githubusercontent.com/25507937/115988043-bb969580-a5af-11eb-81cf-6c98e1ed1f20.png">
