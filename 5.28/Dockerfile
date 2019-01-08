FROM perl:5.28

RUN cpanm -q --notest Dist::Zilla \
    Dist::Zilla::PluginBundle::MSCHOUT \
    Test::Pod \
    Test::Pod::Coverage \
    Pod::Coverage::TrustPod && rm -rf $HOME/.cpanm

