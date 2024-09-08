Last login: Wed Jul 17 05:38:02 on ttys079
(base) <<<
<<< steven@ogPro~
>>> conda activate simple                         05:40.42 Wed Jul 17 2024 >>>
>>> (simple) <<<
>>> <<< steven@ogPro~
>>> python -m venv venv                           05:41.56 Wed Jul 17 2024 >>>

(simple) <<<
<<< steven@ogPro~
>>> cd /Users/steven/Pictures/Comics              05:42.02 Wed Jul 17 2024 >>>
>>> (simple) <<<
>>> <<< steven@ogPro~/Pictures/Comics
>>> 100                                           05:42.15 Wed Jul 17 2024 >>>
>>> (simple) <<<
>>> <<< steven@ogPro~/Pictures/Comics/100
>>> gallery-init                                  05:42.23 Wed Jul 17 2024 >>>
>>> Creating a Simple Photo Gallery...
>>> Creating the gallery config...
>>> You can answer the following questions in order to set some important gallery properties. You can also just press Enter to leave the default and change it later in the gallery.json file.
>>> What is the title of your gallery? (default: "My Gallery")
>>> 100
>>> What is the description of your gallery? (default: "Default description of my gallery")

Which image should be used as background for the header? (default: "")

What is your site URL? This is only needed to better show links to your galleries on social media (default: "")

Gallery config stored in gallery.json
Copying gallery template files...
Moving all photos and videos to ./public/images/photos...
Simple Photo Gallery initialized successfully!
(simple) <<<
<<< steven@ogPro~/Pictures/Comics/100
>>> deactivate                                    05:42.34 Wed Jul 17 2024 >>>
>>> zsh: command not found: deactivate
>>> (simple) <<<
>>> <<< steven@ogPro~/Pictures/Comics/100
>>> gallery-init --force                          05:42.40 Wed Jul 17 2024 >>>
>>> A Simple Photo Gallery already exists at the specified location, but will be overwritten.
>>> Creating a Simple Photo Gallery...
>>> Creating the gallery config...
>>> You can answer the following questions in order to set some important gallery properties. You can also just press Enter to leave the default and change it later in the gallery.json file.
>>> What is the title of your gallery? (default: "My Gallery")

What is the description of your gallery? (default: "Default description of my gallery")

Which image should be used as background for the header? (default: "")

What is your site URL? This is only needed to better show links to your galleries on social media (default: "")

Gallery config stored in gallery.json
Copying gallery template files...
Moving all photos and videos to ./public/images/photos...
Simple Photo Gallery initialized successfully!
(simple) <<<
<<< steven@ogPro~/Pictures/Comics/100
>>> conda activate simple                         05:42.49 Wed Jul 17 2024 >>>
>>> (simple) <<<
>>> <<< steven@ogPro~/Pictures/Comics/100
>>> conda deactivate                              05:42.57 Wed Jul 17 2024 >>>

(base) <<<
<<< steven@ogPro~/Pictures/Comics/100
>>> deactivate                                    05:43.02 Wed Jul 17 2024 >>>
>>> DeprecationWarning: 'source deactivate' is deprecated. Use 'conda deactivate'.
>>> (base) <<<
>>> <<< steven@ogPro~/Pictures/Comics/100
>>> conda deactivate                              05:43.04 Wed Jul 17 2024 >>>

<<<
<<< steven@ogPro~/Pictures/Comics/100
>>> cd                                            05:43.08 Wed Jul 17 2024 >>>
>>> <<<
>>> <<< steven@ogPro~
>>> source ~/.zshrc                               05:43.11 Wed Jul 17 2024 >>>

(base) <<<
<<< steven@ogPro~
>>> conda activate simple                         05:43.17 Wed Jul 17 2024 >>>
>>> (simple) <<<
>>> <<< steven@ogPro~
>>> python -m venv venv                           05:43.23 Wed Jul 17 2024 >>>

(simple) <<<
<<< steven@ogPro~
>>> source venv/bin/activate                      05:43.32 Wed Jul 17 2024 >>>

(venv) (simple) <<<
<<< steven@ogPro~
>>> cd /Users/steven/Pictures/Comics/100          05:43.47 Wed Jul 17 2024 >>>
>>> (venv) (simple) <<<
>>> <<< steven@ogPro~/Pictures/Comics/100
>>> gallery-init                                  05:43.54 Wed Jul 17 2024 >>>
>>> A Simple Photo Gallery already exists at the specified location. Set the --force parameter if you want to overwrite it.
>>> (venv) (simple) <<<
>>> <<< steven@ogPro~/Pictures/Comics/100
>>> gallery-init --force                          05:43.58 Wed Jul 17 2024 >>>
>>> A Simple Photo Gallery already exists at the specified location, but will be overwritten.
>>> Creating a Simple Photo Gallery...
>>> Creating the gallery config...
>>> You can answer the following questions in order to set some important gallery properties. You can also just press Enter to leave the default and change it later in the gallery.json file.
>>> What is the title of your gallery? (default: "My Gallery")

Which image should be used as background for the header? (default: "")

Gallery config stored in gallery.json
Copying gallery template files...
Moving all photos and videos to ./public/images/photos...
Simple Photo Gallery initialized successfully!
(venv) (simple) <<<
<<< steven@ogPro~/Pictures/Comics/100
>>> gallery-build --force                         05:44.04 Wed Jul 17 2024 >>>
>>> Building the Simple Photo Gallery...
>>> Generating thumbnails...
>>> New thumbnails generated: 200
>>> Generating the images_data.json file...
>>> The image descriptions are stored in images_data.json. You can edit the file to add more descriptions and build the gallery again.
>>> Creating the index.html...
>>> The gallery was built successfully. Open public/index.html to view it.
>>> (venv) (simple) <<<
>>> <<< steven@ogPro~/Pictures/Comics/100
>>>                                            05:44.34 Wed Jul 17 2024 >>>