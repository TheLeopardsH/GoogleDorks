# GoogleDorks
    Note :Combination of these google dorks give inormous power for OSINT.I would keep updating it with time
    
    site: Shows results to specific site for john carrier. 
    Example: site:facebook.com  John carrier

    intitle: Restricts results to titles of webpages. 
    Example: intitle:”Jobs in Defence”

    inurl: Restricts results to the URL of a website. 
    combination of inurl and site
    Example: inurl:about site:indeed.com

    filetype: Searches for specific filetypes based on the extensions.
    Example: filetype:pdf site:indeed.com

    link: Searches for pages linking to a specified URL.
    Note:Google killed this operator in 2017, but it does still show some results—they likely aren’t particularly accurate though
    Example: link:www.indeed.com

    cache: Searches for a cached copy of a webpage when it was indexed by Google. 
    Example: cache:lums.edu.pk
    
    - sign remove the results from that name(may be site or titles)
    jobs -indeed
    
    Find non-secure pages
    Example:indeed.com inurl:-https
    
    Finding subdomains alongwith removal of www results
    Example:site:*.indeed.com -www
