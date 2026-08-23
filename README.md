# Spark Science Foundation

Official website for **Spark Science Foundation**, a concept-first science coaching institute in Padmanabhanagar, Bangalore. The website helps students and parents explore academic programs for Classes 9, 10, 11, and 12, review learning resources, and contact the institute for admissions or a demo class.

**Live website:** [sparksciencefoundation.netlify.app](https://sparksciencefoundation.netlify.app/)

## Highlights

- Responsive landing page designed for students and parents
- Dedicated course pages for Classes 9, 10, 11, and 12
- Support for CBSE, ICSE, PUC, JEE/NEET Foundation, and K-CET preparation
- Downloadable syllabus, notes, and study material PDFs
- Course-focused calls to action for syllabus access and admissions
- Gallery featuring the institute's classrooms, tests, events, and activities
- WhatsApp, phone, email, Instagram, and Google Maps contact links
- Information about faculty, small batches, progress tracking, and individual attention

## Project Structure

```text
.
└── app/
    ├── index.html
    ├── class9.html
    ├── class10.html
    ├── class11.html
    ├── class12.html
    ├── logo.jpg
    ├── Farewell.jpg
    ├── Farewell 1.jpg
    ├── Saraswathi pooja.jpg
    ├── Test 1.jpg
    ├── Test 2.jpg
    ├── DEMO_MATERIAL.pdf
    ├── class11-kinetic.pdf
    ├── class11-syllabus.pdf
    └── class11-thermodynamics.pdf
```

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts: Fraunces and Inter
- Static hosting with Netlify

There is no build process or package manager required. The pages and assets can be served directly from the `app` directory.

## Run Locally

From the project root, start any local static server. For example, with Python:

```bash
python -m http.server 8000 --directory app
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

You can also open `app/index.html` directly, although a local server is recommended so that all links and assets behave consistently.

## Deploy With Netlify

To deploy this project from GitHub:

1. Create a new site in Netlify and connect the GitHub repository.
2. Set the **publish directory** to `app`.
3. Leave the **build command** empty.
4. Deploy the site.

Every push to the configured branch will trigger a new deployment.

## Contact

- **WhatsApp:** [+91 97313 85870](https://wa.me/919731385870)
- **Landline:** [080-26394711](tel:08026394711)
- **Email:** [sparksciencefoundation2010@gmail.com](mailto:sparksciencefoundation2010@gmail.com)
- **Instagram:** [@sparksciencefoundation2010](https://www.instagram.com/sparksciencefoundation2010)
- **Address:** No. 169, RK Layout, T. Timmaiah Road, Kidney Foundation Road, Padmanabhanagar, Bangalore 560070

## License

This repository contains the website and branded educational materials for Spark Science Foundation. Content, images, logos, and PDF resources are intended for the institute's website and should not be reused without permission.