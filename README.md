# wftest
../act -l
../act  -e act_test/pr.json pull_request

../act  -e act_test/ph.json --env GITHUB_REF_NAME=main push 