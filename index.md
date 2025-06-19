---
layout: default
---

<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, shrink-to-fit=no, viewport-fit=cover">
<style>
* {
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    touch-action: pan-y pinch-zoom;
}

/* Base styles for consistent sizing */
html {
    overflow-x: hidden !important;
    width: 100%;
    font-size: 16px;
    line-height: 1.6;
    -webkit-text-size-adjust: none;
    text-size-adjust: none;
    -webkit-tap-highlight-color: transparent;
}

body {
    max-width: 100%;
    margin: 0 auto;
    padding: 80px 30px 0;
    font-size: 1rem;
    overflow-x: hidden !important;
    width: 100%;
    touch-action: manipulation;
    -webkit-overflow-scrolling: touch;
}

/* Project image sizing */
.project-image {
    width: 500px;
    height: 500px;
    margin: 20px auto;
    display: block;
    object-fit: cover;
    max-width: 100%;  /* Ensure images don't cause overflow */
}

.project-image2 {
    width: 500px;
    height: 500px;
    margin: 20px auto;
    display: block;
    object-fit: cover;
    max-width: 100%;  /* Ensure images don't cause overflow */
}

/* Large screens (1024px and below) */
@media screen and (max-width: 1024px) {
    html {
        font-size: 14px;
        overflow-x: hidden;
        width: 100%;
        position: relative;
    }
    
    body {
        padding: 60px 15px 0;
        overflow-x: hidden;
        width: 100%;
        max-width: 100vw;
    }
    
    .wrapper {
        overflow-x: hidden;
        width: 100%;
        max-width: 100vw;
        padding: 0 10px;
    }
    
    .project-image, .project-image2 {
        width: 450px;
        height: 450px;
        max-width: 95%;
        margin: 15px auto;
        object-fit: cover;
    }
}

/* Medium screens (768px and below) */
@media screen and (max-width: 768px) {
    html {
        font-size: 13px;
        overflow-x: hidden !important;
        width: 100%;
        touch-action: manipulation;
        -webkit-text-size-adjust: 100%;
    }
    
    body {
        overflow-x: hidden !important;
        width: 100%;
        max-width: 100vw;
        margin: 0;
        padding: 60px 15px 0;
    }
    
    .project-image, .project-image2 {
        width: 400px;
        height: 400px;
        max-width: 90%;
    }
}

/* Small screens (480px and below) */
@media screen and (max-width: 480px) {
    html {
        font-size: 11px;
        overflow-x: hidden !important;
        width: 100%;
        -webkit-text-size-adjust: none !important;
        -moz-text-size-adjust: none !important;
        -ms-text-size-adjust: none !important;
        text-size-adjust: none !important;
        touch-action: pan-y;
        -webkit-overflow-scrolling: touch;
        max-width: 100vw;
        min-height: -webkit-fill-available;
    }
    
    body {
        overflow-x: hidden !important;
        width: 100%;
        max-width: 100vw;
        margin: 0;
        padding: 60px 15px 0;
        -webkit-overflow-scrolling: touch;
        min-height: -webkit-fill-available;
        position: fixed;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
    }
    
    .wrapper {
        overflow-x: hidden !important;
        width: 100%;
        max-width: 100vw;
        height: 100%;
        overflow-y: auto;
        -webkit-overflow-scrolling: touch;
    }
    
    .project-image, .project-image2 {
        width: 350px;
        height: 350px;
        max-width: 85%;
    }
}

/* Content sizing */
.wrapper {
    max-width: 1400px;
    margin: 0 auto;
    padding: 0 30px;
    overflow-x: hidden;  /* Prevent wrapper overflow */
}

section {
    font-size: 1.1rem;
    line-height: 1.6;
    max-width: 100%;  /* Ensure sections don't overflow */
}

h1 {
    font-size: 3em;
    margin-bottom: 0.7em;
}

h2 {
    font-size: 2.5em;
    margin-bottom: 0.7em;
}

h3 {
    font-size: 2em;
    margin-bottom: 0.7em;
}

p, li {
    font-size: 1.1rem;
    margin-bottom: 1em;
}

/* GitHub Profile Link Style */
.view a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #2ea44f;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    transition: background-color 0.3s ease;
}

.view a:hover {
    background-color: #2c974b;
}

/* Project Button Style */
.project-button {
    display: inline-block;
    padding: 8px 16px;
    background-color: #0366d6;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 500;
    margin-top: 10px;
    margin-right: 10px;
    transition: background-color 0.3s ease;
}

.project-button:hover {
    background-color: #0245a3;
}

/* GitHub Button Style */
.github-button {
    display: inline-block;
    padding: 8px 16px;
    background-color: #24292e;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 500;
    margin-top: 10px;
    transition: background-color 0.3s ease;
}

.github-button:hover {
    background-color: #2f363d;
}

/* Education container styles */
.education-container {
    margin: 20px 0;
}

.education-item {
    background-color: #f8f9fa;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 15px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: transform 0.2s ease;
}

.education-item:hover {
    transform: translateY(-2px);
}

.education-item h3 {
    color: #0366d6;
    margin: 0 0 10px 0;
    font-size: 1.2em;
}

.education-details {
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: #586069;
}

.education-details .institution {
    font-weight: 500;
    margin: 0;
}

.education-details .year {
    margin: 0;
    font-style: italic;
}

/* Desktop Styles */
@media screen and (min-width: 1250px) {
    body {
        overflow-x: hidden;
        max-width: 1400px;
    }
    
    .container {
        max-width: 1200px;
        padding: 0 2rem;
    }
    
    h1 {
        font-size: 2.5rem;
    }
    
    h2 {
        font-size: 2rem;
    }
    
    h3 {
        font-size: 1.5rem;
    }
    
    p {
        font-size: 1rem;
    }
    
    .project-image {
        max-width: 90%;
        height: auto;
    }
}

/* Medium-large screens */
@media screen and (min-width: 1024px) and (max-width: 1249px) {
  body {
    overflow-x: hidden;
    zoom: 0.9;
    -moz-transform: scale(0.9);
    -moz-transform-origin: 0 0;
  }
  
  .container {
    max-width: 1100px;
    padding: 0 2rem;
  }
  
  h1 {
    font-size: 2.3rem;
  }
  
  h2 {
    font-size: 1.8rem;
  }
  
  h3 {
    font-size: 1.4rem;
  }
  
  p {
    font-size: 1rem;
  }
  
  .project-image {
    max-width: 85%;
    height: auto;
  }
}

/* Add to the style section */
.project-separator {
    border: 0;
    height: 1px;
    background-color: #e1e4e8;
    margin: 30px 0;
    width: 100%;
}

/* Add to the style section */
table th {
    text-align: center;
}

/* Add Power BI Dashboard styles */
.powerbi-container {
    width: 100%;
    max-width: 1140px;
    margin: 20px auto;
    overflow: hidden;
    position: relative;
    padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
    height: 0;
}

.powerbi-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}

/* Responsive adjustments for Power BI */
@media screen and (max-width: 768px) {
    .powerbi-container {
        padding-bottom: 75%; /* Slightly taller on mobile */
    }
}
</style>

# Aspiring Health Data Scientist & Bioinformatician

📍 United States

Hi, I’m Neela. I am a data enthusiast studying Applied Mathematics with a Bioinformatics minor at Texas A&M. I work at the intersection of math, biology, and tech, with experience in NGS data processing, differential expression analysis, and building custom Python/R pipelines. My focus is on data science, biostatistics, and healthcare equity. I plan to pursue a master’s in computational biology or bioinformatics to further this work.

## Education

| Degree | Institution | Year |
|:------:|:----------:|:----:|
| BSc., Applied Mathematics (BIO); Bioinformatics Minor | Texas A&M University | May 2026 |




## Skills

* **Programming Languages**: Python, R, SQL, JavaScript, MATLAB
* **Data Analysis**: Pandas, PySpark, NumPy, Matplotlib
* **Machine Learning**: Scikit-learn, TensorFlow
* **Data Visualization**: Tableau, Power BI 
* **AI/ML**: LLMs, Speech Recognition, APIs
* **Tools**: Git, GitHub, VSCode, Google Cloud Platform

---

## Featured Projects

### 1. Transcriptomic Analysis of Mouse Cancer Models
<img src="./assets/img/dataviz.png" class="project-image" alt="Data Visualization">
* **Description**: Analyzed long-read RNA sequencing data from tumor and control tissue samples in a mouse model to investigate cancer-associated transcriptomic changes. Focused on identifying alternative splicing events and novel isoforms. Performed basecalling, alignment, and isoform quantification using tools designed for long-read data, and compared expression profiles between conditions.

* **Skills**: Long-read RNA-Seq, ONT/Nanopore data, Minimap2, Bash scripting, UNIX, data visualization, biological interpretation

* **Key Features**: Real-time voice processing, natural dialogue, witty responses, LLM

[View Live Project](https://voice-to-voice-llm.vercel.app){: .project-button} [View on GitHub](https://github.com/zanjeel/Voice-to-Voice-LLM){: .github-button}

<hr class="project-separator">




### 2. Implication of circadian rhythms in the generation of RNAs isoforms
* **Description**: Conducted differential gene expression analysis on RNA-Seq data from mouse tissue samples to study the molecular effects of arrhythmic versus non-rhythmic feeding conditions in cancer progression. Processed FASTQ files, performed quality control, aligned reads to the mouse genome using STAR, and quantified gene expression with featureCounts. Ongoing troubleshooting of module dependencies and batch scripting on the Grace HPRC cluster for scalable computing.

* **Skills**: RNA-Seq, Bash scripting, SLURM, HPC, STAR aligner, featureCounts, UNIX, Emacs, version control

[View Live Project](https://zanjeel.github.io/Automobile-Predictive-Data-Analysis-RStudio/Automobile-Price-Prediction.nb.html){: .project-button} [View on GitHub](https://github.com/zanjeel/Automobile-Predictive-Data-Analysis-RStudio){: .github-button}

<hr class="project-separator">




### 3. Luma – Social Book Ranking App (In Progress)
* **Description**: Developing a minimalistic web-based platform that ranks books based on pairwise comparisons submitted by users, inspired by Beli’s food-ranking interface. Built a Google Sheets backend for initial data collection and is currently implementing sorting logic using Python and Elo rating algorithms. The system adjusts for skews and attempts to reflect individual taste consensus across users.

* **Skills**: Python, Google Sheets, data sorting algorithms, user-centered design, creative UX prototyping, web development (in progress)

* **Key Features**: Multiple ML models comparison, accurate mould forecasting, interactive visualizations

[View Live Project](https://zanjeel.github.io/Weather-Prediction-MachineLearningAlgorithms-HillingdonCouncilUK/MachineLearningModelsforWeatherPrediction.html){: .project-button} [View on GitHub](https://github.com/zanjeel/Weather-Prediction-MachineLearningAlgorithms-HillingdonCouncilUK){: .github-button}



## Contact

* **GitHub**: [https://github.com/neelas7](https://github.com/neelas)
* **LinkedIn**: [Neela-Sardeshpande](https://www.linkedin.com/in/neela-sardeshpande-785026222/){:rel="noopener noreferrer"}
* **Email**: neelasardeshpande@gmail.com

---

_This portfolio is constantly updated with new projects and analyses. Check back regularly for updates!_
