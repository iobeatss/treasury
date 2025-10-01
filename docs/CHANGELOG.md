# À la racine du repo 'treasury'
mkdir -p docs .github/workflows

# (glisse-dépose tes 3 PDF + README_AppendixB_v1.1.md dans ./docs et CHANGELOG.md à la racine)

git add docs/IOB_Treasury_AppendixB_v1.1.pdf \
        docs/IOB_Vesting_Lock_Strategy_v1.1.pdf \
        docs/IOB_Treasury_Lock_Distribution_v1.1_Logo.pdf \
        docs/README_AppendixB_v1.1.md \
        CHANGELOG.md
git commit -m "docs: add Appendix B v1.1 pack (Safe multisig, 66% lock, burn, legal)"
git push origin main
