# NAME

Lingua::Guess - Language identification module which isn't only supporting to
 the European and American languages but also the Asian languages.

# SYNOPSIS

Usage of this module may be going to be following example.

    use Lingua::Guess;

    my $lg = Lingua::Guess->new($host, $port);
    my $text = "Something target text.";
    my $lang = $lg->identify($text);

    # $lang->[0] is include a label and score of top score candidate.
    # In this case. $lang->[0] may be English :)

# DESCRIPTION

Lingua::Guess is one of the language identification module.
This module is characterized by Asian Languages support.

# LICENSE

Copyright (C) 2013. Toshinori Sato (@overlast).

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

Toshinori Sato (@overlast) <overlasting@gmail.com>
