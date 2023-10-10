# data-512-homework_1

## Summary

This repository is the code for collecting and analyzing the traffic from a selection of pages corresponding with academy award winning films. I have included the code, data, and analysis here for future reproducibility of my findings. Data files are marked with the start and end date so that future attempts of reproducing the findings will know what time frames were used. Additionally, below can be found information for installation so that packages and versions of the same software can be used.

## Wikimedia

This analysis uses the wikimedia API which terms of use can be accessed [here](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions). Additionally, the [API documentation](https://wikimedia.org/api/rest_v1/#/Pageviews%20data/get_metrics_pageviews_per_article__project___access___agent___article___granularity___start___end_) and [endpoint](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews) can be found at the given links.

## Intermediary Files

The code in this repository was used to generate the academy_monthly_cumulative_201507-202309.json, academy_monthly_desktop_201507-202309.json, academy_monthly_mobile_201507-202309.json data files which are used in the analysis. Additionally, the image files in the images directory are generated via the analysis.ipynb file.

## Considerations

If generating the data via the pageview.ipynb file, one should take into consideration the time it takes to run. It took my notebook over 10 minutes to run to completion. Another consideration is that the mobile data is a combination of mobile app and web views.

In my analysis, I found that...

## Installation

To utilize this repository, you must first clone it:

```bash
git clone https://github.com/Dreamweaver2k/data-512-homework_1.git
cd ./data-512-homework_1
```

Now, it is necessary to download the proper environment. Please make sure you have [conda](https://conda.io/projects/conda/en/latest/index.html) installed on your system for the next step.

```bash
conda env create -n <your-environment-name> -f environment.yml
```

## License

MIT License
