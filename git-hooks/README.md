git hooks for IPython

add these to your `.git/hooks`

For now, we just have `post-checkout` and `post-merge`,
both of which just update submodules,
so make sure that you have a fully synced repo whenever you checkout or pull.

To use these hooks, you can symlink or copy them to your `.git/hooks` directory.
In `.git/hooks`, do:

    ln -s ../../git-hooks/post-checkout post-checkout
    ln -s ../../git-hooks/post-merge post-merge

