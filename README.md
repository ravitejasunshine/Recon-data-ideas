# Recon-data-ideas.
Finding subdomines data tools
 
 These are the keywords.
 
%api%

%corp%

%internal% 

%dev%

# subdomain tools.

>> www.github.com/nahamsec

# Tool >> 1.crtsh(most using):-

>> %.exampledomain.com

>> exampledomain.%

>> %25api%25.exampledomain.com
       or
 >> crtsh exampledomain.com      

# Tool >> 2.certspotter:-

>> certspotter exampledomain.com

>> certspotter exampledomain.com | wc -l

>> certspotter exampledomain.com | grep dev

>> certspotter exampledomain.com | grep dev | httprobe

#############################################
# alive domains or not using this tool {httprobe} 

www.github.com/tomnomnom

>> certspotter exampledomain.com | httprobe

# cat all.txt |httprobe | wc -l

# Tool >> 3. shodan.io

# Tool >> 4. censys.io
