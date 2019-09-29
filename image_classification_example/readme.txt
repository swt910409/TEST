*This is ReadMe file, your dataset directory does not need contains this file.*
*Directory dataset_dir is your dataset base directory.*
*All text base file must be unix format.*

Directory training:
 - Store image samples for training.
 - Support .jpg/.png/.bmp/.jpeg image files, but only support one image format in one dataset.
 - Support using sub-directory to organize images.

Directory validation:
 - Store image samples for validation.
 - Support .jpg/.png/.bmp/.jpeg image files, but only support one image format in one dataset.
 - Support using sub-directory to organize images.

File training/training.csv, validation/validation.csv
 - Fields split by space.
 - Columns: image_path, label
    No column header, first line is data.
    ‘image_path’ is relative and base on .csv file.
    ‘label’ must be string, can include space.
