# SiteFarm Media
A feature module that provides general media and media library related configuration for the SiteFarm Seed Drupal distribution.

## Creates the following Media Types:

### Audio: Handles audio media files.

#### Fields - Type: 

* Audio file - File

* Category - Taxonomy Term Entity Reference

#### Displays:

* Default

* Media Library

### Document: Handles document and zip files that can be attached to a content type.

#### Fields - Type:

* File - File

* Category - Taxonomy Term Entity Reference

#### Displays:

* Default

* Media Library

### Image: Image media entity type.

#### Fields - Type:

* Image - Image

* Caption - Text (plain)

* Category - Taxonomy Term Entity Reference

#### Displays:

* Default

* Landscape 16x9

* Landscape 4x3

* Media Library

* Photoswipe

* Profile

* Thumbnail

### SVG: Handles SVG image files.

#### Fields - Type:

* SVG - Svg Image

#### Displays:

* Default

* Media Library

### Video: External (Remote) Video media entity type for handling videos from sources like YouTube and Vimeo.

#### Fields - Type:

* Remote video URL - Text (plain)

* Description - Text (formatted, long)

* Category - Taxonomy Term Entity Reference

#### Displays:

* Default

* Landscape 16x9

* Media Library

* Thumbnail
