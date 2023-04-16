"# test-sparse-checkout in windows" 


git clone --no-checkout https://github.com/meyheel/test-sparse-checkout

cd test-sparse-checkout

git sparse-checkout list

git sparse-checkout set

git sparse-checkout list

git sparse-checkout set B/b/1.txt

git sparse-checkout list

git checkout

dir /s
