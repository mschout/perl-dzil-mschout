FROM perl:5.24

RUN cpanm Dist::Zilla \
    Dist::Zilla::PluginBundle::MSCHOUT \
    Test::Pod \
    Test::Pod::Coverage \
    Pod::Coverage::TrustPod && rm -rf $HOME/.cpanm

