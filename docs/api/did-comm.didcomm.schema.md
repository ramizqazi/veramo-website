---
id: did-comm.didcomm.schema
title: DIDComm.schema property
hide_title: true
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## DIDComm.schema property

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

<b>Signature:</b>

```typescript
readonly schema: {
        components: {
            schemas: {
                IPackedDIDCommMessage: {
                    type: string;
                    properties: {
                        message: {
                            type: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                DIDCommMessageMediaType: {
                    type: string;
                    enum: string[];
                    description: string;
                };
                IPackDIDCommMessageArgs: {
                    type: string;
                    properties: {
                        message: {
                            $ref: string;
                        };
                        packing: {
                            $ref: string;
                        };
                        keyRef: {
                            type: string;
                        };
                        options: {
                            $ref: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                IDIDCommMessage: {
                    type: string;
                    properties: {
                        type: {
                            type: string;
                        };
                        from: {
                            type: string;
                        };
                        to: {
                            type: string;
                        };
                        thid: {
                            type: string;
                        };
                        pthid: {
                            type: string;
                        };
                        id: {
                            type: string;
                        };
                        expires_time: {
                            type: string;
                        };
                        created_time: {
                            type: string;
                        };
                        next: {
                            type: string;
                        };
                        from_prior: {
                            type: string;
                        };
                        body: {};
                        attachments: {
                            type: string;
                            items: {
                                $ref: string;
                            };
                        };
                        return_route: {
                            type: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                IDIDCommMessageAttachment: {
                    type: string;
                    properties: {
                        id: {
                            type: string;
                        };
                        description: {
                            type: string;
                        };
                        filename: {
                            type: string;
                        };
                        media_type: {
                            type: string;
                        };
                        format: {
                            type: string;
                        };
                        lastmod_time: {
                            type: string;
                        };
                        byte_count: {
                            type: string;
                        };
                        data: {
                            $ref: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                IDIDCommMessageAttachmentData: {
                    type: string;
                    properties: {
                        jws: {};
                        hash: {
                            type: string;
                        };
                        links: {
                            type: string;
                            items: {
                                type: string;
                            };
                        };
                        base64: {
                            type: string;
                        };
                        json: {};
                    };
                    description: string;
                };
                DIDCommMessagePacking: {
                    type: string;
                    enum: string[];
                    description: string;
                };
                IDIDCommOptions: {
                    type: string;
                    properties: {
                        bcc: {
                            type: string;
                            items: {
                                type: string;
                            };
                            description: string;
                        };
                        recipientKids: {
                            type: string;
                            items: {
                                type: string;
                            };
                            description: string;
                        };
                    };
                    description: string;
                };
                ISendDIDCommMessageArgs: {
                    type: string;
                    properties: {
                        packedMessage: {
                            $ref: string;
                        };
                        messageId: {
                            type: string;
                        };
                        returnTransportId: {
                            type: string;
                        };
                        recipientDidUrl: {
                            type: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                ISendMessageDIDCommAlpha1Args: {
                    type: string;
                    properties: {
                        url: {
                            type: string;
                        };
                        save: {
                            type: string;
                        };
                        data: {
                            type: string;
                            properties: {
                                id: {
                                    type: string;
                                };
                                from: {
                                    type: string;
                                };
                                to: {
                                    type: string;
                                };
                                type: {
                                    type: string;
                                };
                                body: {
                                    anyOf: {
                                        type: string;
                                    }[];
                                };
                            };
                            required: string[];
                        };
                        headers: {
                            type: string;
                            additionalProperties: {
                                type: string;
                            };
                        };
                    };
                    required: string[];
                    deprecated: string;
                };
                IMessage: {
                    type: string;
                    properties: {
                        id: {
                            type: string;
                            description: string;
                        };
                        type: {
                            type: string;
                            description: string;
                        };
                        createdAt: {
                            type: string;
                            description: string;
                        };
                        expiresAt: {
                            type: string;
                            description: string;
                        };
                        threadId: {
                            type: string;
                            description: string;
                        };
                        raw: {
                            type: string;
                            description: string;
                        };
                        data: {
                            anyOf: {
                                type: string;
                            }[];
                            description: string;
                        };
                        replyTo: {
                            type: string;
                            items: {
                                type: string;
                            };
                            description: string;
                        };
                        replyUrl: {
                            type: string;
                            description: string;
                        };
                        from: {
                            type: string;
                            description: string;
                        };
                        to: {
                            type: string;
                            description: string;
                        };
                        metaData: {
                            anyOf: ({
                                type: string;
                                items: {
                                    $ref: string;
                                };
                            } | {
                                type: string;
                                items?: undefined;
                            })[];
                            description: string;
                        };
                        credentials: {
                            type: string;
                            items: {
                                $ref: string;
                            };
                            description: string;
                        };
                        presentations: {
                            type: string;
                            items: {
                                $ref: string;
                            };
                            description: string;
                        };
                        attachments: {
                            type: string;
                            items: {
                                $ref: string;
                            };
                            description: string;
                        };
                        returnRoute: {
                            type: string;
                            description: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                IMetaData: {
                    type: string;
                    properties: {
                        type: {
                            type: string;
                            description: string;
                        };
                        value: {
                            type: string;
                            description: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                VerifiableCredential: {
                    type: string;
                    properties: {
                        proof: {
                            $ref: string;
                        };
                        issuer: {
                            $ref: string;
                        };
                        credentialSubject: {
                            $ref: string;
                        };
                        type: {
                            anyOf: ({
                                type: string;
                                items: {
                                    type: string;
                                };
                            } | {
                                type: string;
                                items?: undefined;
                            })[];
                        };
                        "@context": {
                            $ref: string;
                        };
                        issuanceDate: {
                            type: string;
                        };
                        expirationDate: {
                            type: string;
                        };
                        credentialStatus: {
                            $ref: string;
                        };
                        id: {
                            type: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                ProofType: {
                    type: string;
                    properties: {
                        type: {
                            type: string;
                        };
                    };
                    description: string;
                };
                IssuerType: {
                    anyOf: ({
                        type: string;
                        properties: {
                            id: {
                                type: string;
                            };
                        };
                        required: string[];
                    } | {
                        type: string;
                        properties?: undefined;
                        required?: undefined;
                    })[];
                    description: string;
                };
                CredentialSubject: {
                    type: string;
                    properties: {
                        id: {
                            type: string;
                        };
                    };
                    description: string;
                };
                ContextType: {
                    anyOf: ({
                        type: string;
                        items?: undefined;
                    } | {
                        type: string;
                        items: {
                            anyOf: {
                                type: string;
                            }[];
                        };
                    })[];
                    description: string;
                };
                CredentialStatusReference: {
                    type: string;
                    properties: {
                        id: {
                            type: string;
                        };
                        type: {
                            type: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                VerifiablePresentation: {
                    type: string;
                    properties: {
                        proof: {
                            $ref: string;
                        };
                        holder: {
                            type: string;
                        };
                        verifiableCredential: {
                            type: string;
                            items: {
                                $ref: string;
                            };
                        };
                        type: {
                            anyOf: ({
                                type: string;
                                items: {
                                    type: string;
                                };
                            } | {
                                type: string;
                                items?: undefined;
                            })[];
                        };
                        "@context": {
                            $ref: string;
                        };
                        verifier: {
                            type: string;
                            items: {
                                type: string;
                            };
                        };
                        issuanceDate: {
                            type: string;
                        };
                        expirationDate: {
                            type: string;
                        };
                        id: {
                            type: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                W3CVerifiableCredential: {
                    anyOf: {
                        $ref: string;
                    }[];
                    description: string;
                };
                CompactJWT: {
                    type: string;
                    description: string;
                };
                IMessageAttachment: {
                    type: string;
                    properties: {
                        id: {
                            type: string;
                        };
                        description: {
                            type: string;
                        };
                        filename: {
                            type: string;
                        };
                        media_type: {
                            type: string;
                        };
                        format: {
                            type: string;
                        };
                        lastmod_time: {
                            type: string;
                        };
                        byte_count: {
                            type: string;
                        };
                        data: {
                            $ref: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                IMessageAttachmentData: {
                    type: string;
                    properties: {
                        jws: {};
                        hash: {
                            type: string;
                        };
                        links: {
                            type: string;
                            items: {
                                type: string;
                            };
                        };
                        base64: {
                            type: string;
                        };
                        json: {};
                    };
                    description: string;
                };
                IUnpackDIDCommMessageArgs: {
                    $ref: string;
                    description: string;
                };
                IUnpackedDIDCommMessage: {
                    type: string;
                    properties: {
                        metaData: {
                            $ref: string;
                        };
                        message: {
                            $ref: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
                IDIDCommMessageMetaData: {
                    type: string;
                    properties: {
                        packing: {
                            $ref: string;
                        };
                    };
                    required: string[];
                    description: string;
                };
            };
            methods: {
                getDIDCommMessageMediaType: {
                    description: string;
                    arguments: {
                        $ref: string;
                    };
                    returnType: {
                        $ref: string;
                    };
                };
                packDIDCommMessage: {
                    description: string;
                    arguments: {
                        $ref: string;
                    };
                    returnType: {
                        $ref: string;
                    };
                };
                sendDIDCommMessage: {
                    description: string;
                    arguments: {
                        $ref: string;
                    };
                    returnType: {
                        type: string;
                    };
                };
                sendMessageDIDCommAlpha1: {
                    description: string;
                    arguments: {
                        $ref: string;
                    };
                    returnType: {
                        $ref: string;
                    };
                };
                unpackDIDCommMessage: {
                    description: string;
                    arguments: {
                        $ref: string;
                    };
                    returnType: {
                        $ref: string;
                    };
                };
            };
        };
    };
```
