The next branch
===============

``next`` is a branch that is frequently rebased. It contains patches
implemented in this repository and sent to upstream_. The branch is generated
automatically with `git-assembler`_ and the configuration can be found in
`<.gitassembly>`_.

If your project depends on features that are in the next branch, you should
prefer to use git tags in the format ``next-*``, which are fixed versions of
the next branch. The suffix will usually be represented as the date of when the
tag was created.

Branches that are merged into ``next`` have the prefix ``nx/`` and should exist
only while the respective pull request is still active. Links to the pull
requests should be provided in the assembly file as a comments.

There is also another branch named ``next-base``, which adds this documentation
and the assembly file. Such a branch is updated manually by the maintainer.

.. _upstream: https://github.com/mongomock/mongomock
.. _git-assembler: https://gitlab.com/wavexx/git-assembler
