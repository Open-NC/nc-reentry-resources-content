# NC Reentry Resources Content 

The original [Buncombe County Reentry Resources Hub](http://www.buncombereentryhub.org/) is implemented as a Wordpress website, and individual topic pages were written by a variety of people, so that they don't follow a single standard template.

In the new implementation, content for a topic page for a given county has a strict form:

1. __Common Description__: a block of HTML text with information relevant statewide (or nationally)
2. __Local Description__: a block of HTML text with information relevant to the specific county
3. __National & State Resources__: a list of resources common to all counties
4. __Local Resources__: a list of resources relevant to the specific county
5. __211 Resources__: a list of resources pulled from the 211 database based on categories

where all resources consist of:

- Name
- Short description
- URL
- Category

For counties that do not have tailored content, the topic page will be created only from 1, 3, and 5.

We will need to replicate all the information from the current site, dividing it into common and Buncombe-specific parts. However, before completing that, we need to set up some guidelines for just how the descriptions should be structured and formatted and how resource descriptions should be structured (you can find some resource examples in, e.g., `jurisdictions/buncombe/health/resources_local.json` in the [content repository](https://github.com/CodeForNC/nc-reentry-resources-content). 

The guidelines should be prepared in [this Google doc](https://docs.google.com/document/d/1ohCB0a4YKEJqT9ZyVz26w9EjdCy7irkgoHWz0dl9w7o/edit?usp=sharing).


