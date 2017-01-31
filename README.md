# README
Rules and administration for the use of the GitHub CUSystem organization.

# Who We Are
Supporting four campuses, CU University Information System (UIS) creates, maintains, and administers multiple shared and bespoke systems. On occasion we determine that code and information used in the pursuit of excellent University support should be shared with our campus partners and the general public.

# Rules for Repo Contributors
No one _loves_ rules. However, the use of this organization and repo system is a privelege. Please take a moment to review the following "gates" to see if your code fits here.

1. Public Information => No secrets, encrypted or otherwise. 

    Do not use GitHub-based repos if your code contains secrets of any kind.
    
    A corralary to this is to limit the amount of side-channel information about internal server names. Scrub your hiera or yaml templates before committing please.
    
    Please only select 'public' if you create new repositories under this organization. We have no mandate for private repos.

2. Attribution

    All code must be attributed exactly: "© Regents of the University of Colorado".

3. Generic and public-use

    The code must be of some public utility. A best case of this is the extension or contribution to open-source projects that we already use, e.g., Ansible, Puppet, Oracle Docker, & c.
    
4. Open-Source License

    All code published here must include a license.
    
    Publication of information as an opensource project implies that you and your management have agreed on the applicability of publishing via GitHub and the selection of an appropriate license.
    
    As of JAN-2017 the preferred license is the Apache 2 license due to its favourable consideration of patent protection. Good information here: https://choosealicense.com/

5. README files
   
    All code published here shall include a README file. Contact info is optional and implied by github push and membership anyway.
    
    A README file should include contribution policy, specifically indicating how one goes about working with or contributing to the codebase (direct push, fork-branch-merge request, fork-master-merge, etc.). It's also pretty common to see this information as a separate file if that process is involved.
    
    There's probably quite a lot more that a README should have. This is a situation where more is more.
    
# Supporting Information
Citation and references supporting the use of Opensource licensing and attribution.

## Re Attribution

> I have our answer from legal about how we should mark code should we post it on open source sites. We should include the mark, as follows, and we’re set!

> © Regents of the University of Colorado

-- Email to Steve Taylor from Sharon G., UIS, 10/11/2016

## Re Open-source licensing:

> We’re pretty flexible with which open source license to apply to your code.  My office provides guidance on the different licenses, but for the most part, we let our researchers choose a license based on how you want others to use the code, whether you want them to share modifications, and whether there is any integrated third-party code that requires a specific license (for example, using GPL-licensed code in your program requires you to release your code under GPL as well).  

> It is a bit different when you’re a non-CU researcher and you’re developing code as part of your duties for UIS.  I recommend you discuss your plans to release the code open source with your supervisor first and determine if UIS has preferred licenses to use.   If you have buy-in from your supervisor and there’s no UIS guidance on OSI licenses, then as I mentioned above, you can decide which license to apply.

-- Email to Steve Taylor from Molly M., Technology Transfer, 10/13/2016

#EOF
Steve Taylor, JAN-2017, © Regents of the University of Colorado
