+++
# Display name
name = "Stephen D. Coleman"

# Username (this should match the folder name)
authors = ["admin"]

# Is this the primary user of the site?
superuser = true

# Role/position
role = "MSc student of Bioinformatics"

# Organizations/Affiliations
#   Separate multiple entries with a comma, using the form: `[ {name="Org1", url=""}, {name="Org2", url=""} ]`.
organizations = [ { name = "Cambridge University", url = "" } ]

# Short bio (displayed in user profile at end of posts)
bio = "It's a statistician's life for me."

# Enter email to display Gravatar (if Gravatar enabled in Config)
email = "stcolema@tcd.ie"

# List (academic) interests or hobbies
interests = [
  "Clustering methods",
  "Computational statistics",
  "Immunology"
]

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups = ["Researchers", "Visitors"]

# List qualifications (such as academic degrees)
[[education.courses]]
  course = "MSc in Bioinformatics"
  institution = "Wageningen University & Research"
  year = 2019

[[education.courses]]
  course = "BA in Mathematics"
  institution = "Trinity College, University of Dublin"
  year = 2016

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/widgets/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.

[[social]]
  icon = "envelope"
  icon_pack = "fas"
  link = "#mailto:stcolema@tcd.ie"  # For a direct email link, use "mailto:test@example.org".

[[social]]
  icon = "twitter"
  icon_pack = "fab"
  link = "https://twitter.com/stcolema1"

# [[social]]
#   icon = "google-scholar"
#   icon_pack = "ai"
#   link = "https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ"

[[social]]
  icon = "github"
  icon_pack = "fab"
  link = "https://github.com/stcolema"

# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# [[social]]
#   icon = "cv"
#   icon_pack = "ai"
#   link = "files/cv.pdf"

+++

I am a MSc student currently writing my dissertation as part of the [**Wallace Group**](http://chr1swallace.github.io) in the Department of Medicine at Cambridge University. The dissertation aims to define tissue specific gene sets by clustering gene expression data across multiple tissue types using Multiple Dataset Integration (**MDI**), an unsupervised clustering 
method based upon Dirichlet processes.

Previously I have worked with [**Paul Kirk**](http://www.mrc-bsu.cam.ac.uk/people/in-alphabetical-order/h-to-m/paul-kirk/),
[**Laurent Gatto**](https://lgatto.github.io/) and [**Ollie Crook**](https://www.mrc-bsu.cam.ac.uk/people/in-alphabetical-order/a-to-g/oliver-crook/)
to extend MDI to a semi-supervised predictive tool in spatial proetomics. This is available online in [`tagm-mdi`](https://github.com/stcolema/tagmmdi).

I have also worked with Gerrit Gort, Elias Kaiser and Rachel Schipper to model the Farquhar-van Cammerer-Berry model of photosynthesis. As all of the data for this task is repeated measurements from individual plants, we hope to use mixed-effects models to account for this correlation in the data.

My research interests include Bayesian clustering applied to 'omics data to 
extract biological information. Within 'omics we have huge quantities of data; 
interpreting this and creating a coherent story of disease is a non-tirivial 
problem. My aim is to use Bayesian clustering methods (particularly 
non-parametric methods) in the area of immunology to help contribute to the
understanding of disease. 
