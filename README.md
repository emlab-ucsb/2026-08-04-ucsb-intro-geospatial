## 2026-08-04-ucsb-intro-geospatial

    This is the lesson repository for 2026-08-04-ucsb-intro-geospatial

## Instructions for changing webpages

- Edit .Rmd files in `episodes` folder
- Run `sandpaper::build_lesson(rebuild = TRUE)` (this requires your gitignore file to have /docs in it - add it for now, but don't push the gitignore file later)
- If you run into issues with `renv`, run `sandpaper::no_package_cache()` then re-run `sandpaper::build_lesson()`
- Copy docs from `site/docs` to `docs`
- Push to github (do not push the gitignore file), site should rebuild automatically
