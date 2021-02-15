.. index::
   single: Password Hasher


Hashing and Secure Password
==================================

.. versionadded:: 5.0

    The PasswordHasher component was introduced in Symfony 5.0.

Installation
------------

.. code-block:: terminal

    $ composer require symfony/password-hasher

.. configuration-block::

    .. code-block:: yaml

        # config/security.yml
        security:
            password_hashers:
                Symfony\Component\Security\Core\User\User: plaintext
                App\Entity\User: auto

