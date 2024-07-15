# Competitive Programming in Haskell

## how to run
 1. add executable setting in the cabal file
   
    Example:
    ```
    executable aoj-itp1-1-a
    hs-source-dirs:      src/aoj/itp1
    main-is:             itp1_1_a.hs
    ghc-options:         -threaded -rtsopts -with-rtsopts=-N
    build-depends:       base
                        , haskell-competitive-programming
    default-language:    Haskell2010
    ```

  2. execute the file in through cli
        ```
        cabal run aoj-itp1-1-a
        ```