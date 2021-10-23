## The right way to implement google-signin-unity
1. Import [google-signin-unity](https://github.com/googlesamples/google-signin-unity)
2. Delete Parse/Plugins/ and PlayServiceResolver/
3. Import external-dependency-manager from [unity-jar-resolver](https://github.com/googlesamples/unity-jar-resolver)
4. Rename files as he says https://github.com/googlesamples/google-signin-unity/issues/106
5. Run resolver by Assets/External Dependency Manager/Android Resolver/Resolve (or Force Resolve)
6. Restart unity editor