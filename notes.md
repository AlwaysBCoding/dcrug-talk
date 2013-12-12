# REGEX 1 - No + allowed in front end of email
[A-Z0-9._%-]+@[A-Z0-9.-]+\.[A-Z]{2,4}

# REGEX 2 - Only 2,4 letter domains
[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,4}

# REGEX 3 - All domains
[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,10}

## A lot of rules to keep track of, and I'm really repeating myself here... It would be nice to just write these rules down somewhere and automate this check
## Testing is just about automating the checks you do anyway to see if your code is working
