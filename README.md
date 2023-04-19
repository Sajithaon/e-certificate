# TRUST MODEL BASED ON BLOCKCHAIN FOR VANETS

VANETS USING BLOCKCHAIN

What is VANETS ?

     Vehicle AD-HOC Network Communicate with each other in vehicle-to-vehicle (V2V) 
     Communicate directly with road-side units (RSUs) through vehicle to- infrastructure (V2I) mode

    SECURITY - related cryptography and mechanisms should always be the first priority of any authentication protocol.

    PRIVACY -A vehicle’s private information should be required as less as possible EFFICIENCY
    -The computational cost and storage requirement for keys and certificates
    
 ![WhatsApp Image 2023-04-19 at 20 57 42](https://user-images.githubusercontent.com/131268528/233125270-ef91e706-51a7-4e6e-a998-132413dbe0c8.jpeg)
    

Why blockchain is used?

    It is a distributed ledger technology
 
    It contains a list of data blocks linked through cryptography alogorithm 
 
    It offers:
 
        1.Decentralization 
        2. Traceability 
        3. immutabilty
        4. security 
 
 FRAMEWORK:
 
     * ENTITY LAYER

          A vehicle or a RSU is regarded as  an entity of VANETs which needs
          authentication service.


      * TRUST LAYER

           A consortium blockchain is  deployed along with its native  trusted authorities
           
   ![WhatsApp Image 2023-04-19 at 20 58 08](https://user-images.githubusercontent.com/131268528/233125256-a7f1a258-c3d5-4c93-a81f-9996e85fc947.jpeg)
           
  UTXO Data Structure:
        Unspent transaction output (UTXO), successfully used in Bitcoin

       A token is introduced to represent a one-time guarantee  for authenticity
       Once a receiver gets a token from a sender in the ledger
       It means an authentication request has been sent from the latter entity 
       It represents the proof of the dedicated sender and its authentication activity

 Key elements of UTXO data structure
   ![Wha![WhatsApp Image 2023-04-19 at 20 58 37](https://user-images.githubusercontent.com/131268528/233125244-6c02aa26-7587-403f-99cf-8e9c0794eaff.jpeg)
 
 WORKING MECHANISM
 
        Entity Ei and Ej create their public/private keys locally and register in  their dedicated authorities
              namely T A(Ei) and T A(Ej ), by submitting  their real identities and public keys

        Once an entity (Ei ) is successfully verified by a TA

        The entity enrolls in the consortium blockchain is assigned with a  unique address or an ID, namely ID(Ei)
evaluation 
   
        1.security and privacy analysis
        2.man in middle attack is reduced
        3.identity revealing attack is also reduced
        4.authority abuse attack is minimized 
