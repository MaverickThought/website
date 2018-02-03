+++
title = "Evaluating performance of image segmentation criteria and techniques"
date = 2013-05-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dorit S Hochbaum", "Cheng Lyu", "Erik P Bertelli"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "EURO Journal on Computational Optimization"
publication_short = "EURO J. Comput. Optim."

# Abstract and optional shortened version.
abstract = "The image segmentation problem is to delineate, or segment, a salient feature in an image. As such, this is a bipartition problem with the goal of separating the foreground from the background. An NP-hard optimization problem, the Normalized Cut problem, is often used as a model for image segmentation. The common approach for solving the normalized cut problem is the spectral method which generates heuristic solutions based upon finding the Fiedler eigenvector. Recently, Hochbaum (IEEE Trans Pattern Anal Mach Intell 32(5):889–898, 2010) presented a new relaxation of the normalized cut problem, called normalized cut ' problem, which is solvable in polynomial time by a combinatorial algorithm. We compare this new algorithm with the spectral method and present experimental evidence that the combinatorial algorithm provides solutions which better approximate the optimal normalized cut solution. In addition, the subjective visual quality of the segmentations provided by the combinatorial algorithm greatly improves upon those provided by the spectral method. Our study establishes an interesting observation about the normalized cut criterion that the segmentation which provides the subjectively best visual bipartition rarely corresponds to the segmentation which minimizes the objective function value of the normalized cut problem. We conclude that modeling the image segmentation problem as normalized cut criterion might not be appropriate. Instead, normalized cut ' not only provides better visual segmentations but is also solvable in polynomial time. Therefore, normalized cut ' should be the preferred segmentation criterion for both complexity and good segmentation quality reasons."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "eval_pef_img_seg.jpg"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Network Graphs", "Image Segmentation"]

# Links (optional).
url_pdf = "https://link.springer.com/content/pdf/10.1007%2Fs13675-012-0002-8.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Article", url = "https://link.springer.com/article/10.1007/s13675-012-0002-8"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "eval_pef_img_seg.jpg"
caption = "Images segmentation results for a benchmark image"

+++
