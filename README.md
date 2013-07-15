## Islandora ingest forms

### Description

This repository will be used to store a variety of Islandora ingest forms that anyone can download and use.

You can find the latest versions of the Islandora Solution Pack MODS forms by following these links:

1. [Audio MODS Form](https://github.com/Islandora/islandora_solution_pack_audio/blob/6.x/xml/mods_audio.xml)

2. [Books MODS Form](https://github.com/Islandora/islandora_solution_pack_book/blob/6.x/xml/mods_book.xml)

3. [Image MODS Form](https://github.com/Islandora/islandora_solution_pack_image/blob/6.x/xml/mods_image.xml)

4. [Large Image MODS Form](https://github.com/Islandora/islandora_solution_pack_large_image/blob/6.x/xml/mods_large_image.xml)

5. [PDF MODS Form](https://github.com/Islandora/islandora_solution_pack_pdf/blob/6.x/xml/mods_pdf.xml)

6. [Video MODS Form](https://github.com/Islandora/islandora_solution_pack_video/blob/6.x/install_files/MODS_VIDEO_FORM.xml)

### Use

1. Clone the repo

    `git clone https://github.com/Islandora/islandora_ingest_forms.git`

2. Initialize the submodules (other's contributed forms)

    `cd islandora_ingest_forms`

    `git submodule init`

3. Update submodules to latest versions

   `git submodule foreach git pull origin master`

### Contributing

1. [Fork the repository](https://help.github.com/articles/fork-a-repo)

2. Add your repository as Git submodule like:

`git submodule add https://github.com/yorkulibraries/YUDL-Islandora-forms.git "York University Library"`
 
3. [Submit a pull request](https://help.github.com/articles/creating-a-pull-request) - Make sure you have a README file in your repo that describes what your forms do so other folks can decide if they are potentially helpful.
