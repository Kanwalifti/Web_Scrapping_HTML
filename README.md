# Web Scraping - Mission to Mars:

# Background:
Mars, known as the "Red Planet," is the fourth planet from the Sun and the second-smallest planet in our Solar System, with its size exceeding only that of Mercury. It derives its name from the Roman god of war.

# Project Overview:
In this project, I developed a web application that performs web scraping on multiple websites to gather data related to the Mission to Mars. The scraped information is then displayed in a unified HTML page, providing users with comprehensive and up-to-date insights about the Mars mission.# Web_Scrapping_HTML

# Step 1 - Scraping:

To begin the scraping process, Jupyter Notebook was employed along with the libraries BeautifulSoup, Pandas, and Requests/Splinter. All the scraping and analysis tasks were completed within a Jupyter Notebook file named "mission_to_mars.ipynb."

# NASA Mars News:

The first step involved scraping the NASA Mars News Site to extract the latest News Title and Paragraph Text. The obtained result is as follows:
Title:  NASA's MAVEN Observes Martian Night Sky Pulsing in Ultraviolet Light
Paragraph:  Vast areas of the Martian night sky pulse in ultraviolet light, according to images from NASA’s MAVEN spacecraft. The results are being used to illuminate complex circulation patterns in the Martian atmosphere.

# JPL Mars Space Images - Featured Image:

For this step, I visited the URL for JPL's Featured Space Image and utilized Splinter to navigate the website. The objective was to find the image URL for the current Featured Mars Image and store it in a variable called "featured_image_url."

To ensure the image URL points to the full-size .jpg image, necessary adjustments were made, and a complete URL string for this image was saved. The output displays the resulting URL for the featured Mars image.

https://www.jpl.nasa.gov/spaceimages/images/mediumsize/PIA19346_ip.jpg





