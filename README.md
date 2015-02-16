# NAME

Lingua::EN::Nickname - Genealogical nickname matching (Liz=Beth)

# SYNOPSIS

    use Lingua::EN::Nickname;

    # Equivalent first names?
    $score= nickname_eq( $firstn_0, $firstn_1 );

    # Full, expanded, name(s) 
    @roots= nickroot( $firstn );

# DESCRIPTION

Nicknames, alternate spellings, and alternate etymological derivations
make checking first name equivalence nearly impossible.
This module will tell you that 'Maggie', 'Peg', and 'Margaret' are all
probably the same name.

# SOURCES

- USGenWeb Project 
[http://www.usgenweb.com/researchers/nicknames.html](http://www.usgenweb.com/researchers/nicknames.html)
- TNGenWeb Project 
[http://www.tngenweb.usit.com/franklin/frannick.htm](http://www.tngenweb.usit.com/franklin/frannick.htm)
- Chesnut Family Pages 
[http://www.users.mis.net/~chesnut/pages/nicknams.htm](http://www.users.mis.net/~chesnut/pages/nicknams.htm)
- Ultimate Family Tree 
[http://www.uftree.com/UFT/HowTos/SettingOut/nickname1.html](http://www.uftree.com/UFT/HowTos/SettingOut/nickname1.html)

# TODO

- Hire a team of experts to provide a more scientific, 
statistically accurate Name Etymology source file.
- Create more phoenetically-based sub-regexes.
- Detect simple monosyllabic truncation nicknames, 
be less certain about them, but match more.
- Pay more attention to gender.

# AUTHOR

Brian Lalonde, <brian@webcoder.info>

# SEE ALSO

perl(1)
