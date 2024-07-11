I. Overview This project was created by using the empty-skeleton template. The project adopts and exemplifies the proposal-accept design pattern.

Client can create a ClientAccountMusicStoreProposal contract. StoreAdmin can exercise ReviewAccountStore to check client proposal and approve it. StoreAdmin can either Reject or Review the proposal. Upon getting approved, a Account contract is created.

II. Workflow client creates a ClientAccountMusicStoreProposal contract StoreAdmin exercises Review to check client proposal and approve it StoreAdmin exercises RejectStoreAccountProposal with a reason: "Client had issues before in the store" client exercises Cancel to cancel the proposal StoreAdmin exercises Review, if approved a account is created

III. Challenge(s) SDK version is 2.8.5 and the code itself does not cause any issues/errors The project was created by using empty-skeleton

IV. Compiling & Testing To compile and test, run the pre-written script in the Test.daml under /daml OR run:

$ daml start
